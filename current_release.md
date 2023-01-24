The version published at this time contains breaking and non-breaking changes.


#### 🐛 Bugfixes

* [#559](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/559) [#912](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/559) ad, au, cp, hy and tn http redirections fixed - [#xxx](https://github.com/inspire-eu-validation/ets-repository/pull/xxx)
* [#661](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/661) application/atom+xml and text/xml added as valid types - [#xxx](https://github.com/inspire-eu-validation/ets-repository/pull/xxx)
* [#852](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/852) hy-n-as.b.1 geometry manual check - [#xxx](https://github.com/inspire-eu-validation/ets-repository/pull/xxx)
* [#854](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/854) noAccessText error message updated - [#xxx](https://github.com/inspire-eu-validation/ets-repository/pull/xxx)
* [#873](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/873) Topic category validation fixed - [#xxx](https://github.com/inspire-eu-validation/ets-repository/pull/xxx)
* [#883](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/883) nz-ia.a.2 SpecificExposedElementTypeValue path fix - [#xxx](https://github.com/inspire-eu-validation/ets-repository/pull/xxx)
* [#900](https://github.com/INSPIRE-MIF/helpdesk-validator/issues/900) WFS Direct dependency updated - [#xxx](https://github.com/inspire-eu-validation/ets-repository/pull/xxx)



#### 🚀 Validator UI

* [#35](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/issues/35) Modify default parameters in metadata urls to ensure ISO compliance - [#41](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/pull/41)
* [#31](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/issues/31) Wrong dependency between WFS Conformance Classes - [#43](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/pull/43)
* [#30](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/issues/30) Indications on the time that tests reports are kept - [#40](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/pull/40)
* [#29](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/issues/29) Wrong title in the single test report page - [#39](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/pull/39)
* [#26](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/issues/26) "Resource type" filter does not work in production - [#38](https://github.com/inspire-eu-validation/INSPIRE-Validator-UI/pull/38)



#### Deployment instructions

The section containing the deployment process using Docker image and troubleshooting section. You can also find these in the [training material](https://github.com/INSPIRE-MIF/helpdesk-validator/blob/master/training%20material/2020-09-16_Docker_deployment_instructions.md)

```CMD
docker login docker.pkg.github.com 
#Provide Github credentials
docker run --name inspire-validator -d -p 8090:8090 -v ~/etf:/etf docker.pkg.github.com/inspire-mif/helpdesk-validator/inspire-validator:2023.0
#Launches a container with the image, exposing the UI in port 8090 through the same port in the host machine, and uses a volume in the local file system, on the directory ~/etf
```
##### Modifying the Docker image

In the inspire-validator ZIP file, you can find all the resources needed to generate the Docker image from this release. If you would like to tweak anything from it, you can modify any of its contents (Dockerfile, entrypoint file, configuration files... ), then execute the command
```
docker build -t [IMAGE_NAME]:[VERSION]
```
You can run this again using the run command
```
docker run --name inspire-validator -d -p 8090:8090 -v ~/etf:/etf [IMAGE_NAME]:[VERSION]
```
##### Deployment on production host

The Docker image is set up to run at localhost to be deployed on any machine. However, users may need to access their validator on a dedicated host, usually with a domain name. For proper functioning of the validator, the UI and correct rendering of Test Reports, the validator needs to be configured to run on a domain.

If you want to run the webapp in another host, you can change the configuration file, inside the .war file inside the inspire-validator zip file accompanying this release, at ```WEB-INF/classes/etf-config.properties```, and modify the `etf.webapp.base.url` property. 
It is also necessary to configure the Validator UI properties in order to properly point to the ETF. Thus, it is necessary to modify the configuration values in the /validator/js/config.js file inside the ui.zip (to point to the corresponding host domain).
Then you can proceed to the build process described in the previous point.

##### Exposing the validator through a proxy

Usually, host machines are connected to a private network that accesses the Internet through a proxy. The Docker client needs to be configured to make use of this proxy, in order to be able to build the image and set up running the container.

For the build process, you need to add the following arguments to the command
```
--build-arg http_proxy=[HTTP_PROXY_URL:PORT]  --build-arg https_proxy=[HTTPS_PROXY_URL:PORT]  --build-arg no_proxy=127.0.0.1,localhost,*.<my-domain>
```
For the run command, you need to add the environment variables to it
```
--env http_proxy=[HTTP_PROXY_URL:PORT]  --env https_proxy=[HTTPS_PROXY_URL:PORT]  --env no_proxy=127.0.0.1,localhost,*.<mydomain>
```
These can also be set up in the Dockerfile, using the keyword ENV

For more information please check out https://docs.docker.com/network/proxy

For further configuration, please download the file inspire-validator-2023.0.zip and follow the instructions in the README.md file inside the .zip file.