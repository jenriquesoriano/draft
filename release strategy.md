# Introduction

## Current Situation
The INSPIRE Validation & conformity testing framework consists of Abstract and Executable Testsuites, of the ETF framework and User Interface and of additional tools such as the Linkage Checker. It helps INSPIRE implementers to understand whether their data sets and network services are compliant to the technical guidance. Resources need to fulfill a wide set of requirements to qualify as fully compliant.
The framework was initially made available in 2016 and has since given data providers feedback to implement the requirements correctly. Before the initial availability of the framework, there was often a lot of ambiguity in what exactly is compliant and what not, which reduced interoperability. In 2019, the INSPIRE monitoring was first based on direct harvesting and compliance testing of data sets, network services and metadata. This is a first step to continuous, data driven monitoring, with fewer manual steps and corrections applied by intermediate SDIs. 
As of late 2019, the monitoring for 2019 has just been completed, and implementers have relied heavily on the framework and associated tools to make their resources fit for INSPIRE. 

## Desired Situation
When reviewing the current situation, a few aspects come to mind that would help to make conformity testing a more straightforward task. To support both INSPIRE implementers and the central reporting optimally, we propose the following for the INSPIRE validation and conformity testing framework:
* Create transparency into Release Planning process and into deployment states
* Provide stable conformity criteria with enough lead time before the monitoring period
* Establish data-driven testing 
* Communicate changes and their impact to the community

# Release Planning
At the core of the release planning strategy is the annual major release. This is the release that encompasses the rules that will be applied in the end-of-year reporting. To give tool developers and INSPIRE implementers sufficient time to adjust, this release will be made with significant lead time to the monitoring period.

In order to provide users with an environment where developments can be adequately tested, different test environments are offered, where the ATS/ETS developed will be tested on a specific instance of the ETF.
There will be different instances of the ETF deploying different branches of the ATS/ETS/ETF set, with different purposes
* Production instance: stable deployment with official and proven ATS/ETS for the current year's report
* Staging instance: which will contain a pre-publication version of the production
* Beta instance: this environment will contain a version corresponding to the following year's application, so users can choose to validate against the current year's version or the following year's version

The different versions incorporated into these environments may contain different developments, both at the ATS/ETS and ETF levels.
The following types of functionalities to be incorporated are established according to the relevance of the changes introduced in each development, as well as to the impact it has on the validations to be carried out
* Breaking changes:
  * Corresponding to an implementation that makes the compliance more restrictive and difficult to pass
  * New tests
* Non-Breaking changes:
  * Implementation reducing restriction for the correct compliance in a requirement
  * Minor changes to the interface that add new functionalities to the interface but it has no effect on the tests
* Hotfix: detected bug that needs to be implemented and extended as soon as possible to the different instances

In order to facilitate reporting at the end of the year, a fundamental aspect is that the community is adequately informed of the versions to be released, as well as being given enough time to accommodate the data to be reported on a stable, unvarying and reliable version.
Globally, a work schedule is established for the annual report in which the focus is mainly on concentrating the breaking-changes in the first half of the year, so that by June of each year, there is a stable version on which to test the data and where the changes introduced up to the end of the year do not impact more restrictively on the validations to be made on the reporting information.
Thus, the following schedule of versions can be conceived in accordance with the objective of offering the version used in the annual report at mid-year that can be used from that moment for the preparation of data aligned with the requirements to be met at the end of the year.
* **v2020.1 - 15/03/2020.** It includes a first batch of binding developments to the end-2020 report, as well as improvements to the ETF tool.
* **v2020.2 - 15/06/2020.** This version includes all the requirements and restrictions to incorporate the annual report, so that users can use it from now on to adapt their data appropriately until the end of the year
* **v2020.3 - 15/09/2020.** The version published at this time contains all the restrictions and possible non-breaking changes or HotFixes, that is to say developments that do not imply additional work for the report but that can lower the degree of restriction of the requirements or correct existing bugs.
This version will be used for the evaluation of the annual report.
* **v2021.b - 15/09/2020.** In addition, a version will be published that incorporates the changes to be evaluated in the following year's report, so that those community members who want to test them will have it at their disposal.
* **v2021.0 - 15/01/2021.** After the conclusion of the reporting cycle, a first version of the TSAs/STEs and the ETF to be used in the 2021 reporting cycle will be published in the production environment.
From this version onwards, the same release philosophy will be followed, so that the community has a clear understanding of what is to be released, the functionalities offered and the scope of these developments.

These announced versions must be orchestrated not only in terms of infrastructure and deployment environments, but also in terms of managing the various branches in the community repository.
Thus, in order to clarify the operation between the different branches and the deployment environments where the ATS/ETS will be able to run, the diagrams below are included:

## v2020.1 - 15/03/2020
This first version v2020.1 to be deployed in the production instance on 03/15/2020 includes breaking-changes, i.e. new requirements and developments that directly impact the report to be made. 
As you can see, it is based on the current release v1.0.8, which is deployed in production environment.
All issues that come in the period prior to the release, whether they are breaking changes, non-breaking changes or HotFixes will be deployed as soon as they have been developed in the staging environment, as usual. 
If a production deployment is needed before the HotFix date, the corresponding branch v1.0.8.1 will be created and the production deployment will follow.
Finally, according to the planned date, the validated developments will be taken from the staging branch, creating the branch v2020.1 that will be deployed merge in the master branch and deployed in the production environment. 
This way, the reference version from this release becomes v2020.1

![v2020.1](https://github.com/jenriquesoriano/draft/blob/release-strategy/img/ETF%20INSPIRE%20Validator-Release%20management%20diagrams-2020.1_202001291530.png "v2020.1")

![v2020.2](https://github.com/jenriquesoriano/draft/blob/release-strategy/img/ETF%20INSPIRE%20Validator-Release%20management%20diagrams-2020.2_202001291530.png "v2020.2")

![v2020.3](https://github.com/jenriquesoriano/draft/blob/release-strategy/img/ETF%20INSPIRE%20Validator-Release%20management%20diagrams-2020.3_202001291530.png "v2020.3")

![v2021.0](https://github.com/jenriquesoriano/draft/blob/release-strategy/img/ETF%20INSPIRE%20Validator-Release%20management%20diagrams-2021.0_202001291530.png "v2021.1")





#TESTS

TEST1
![TEST1] (/img/v2021.3.png)


TEST2
![TEST2] (./img/v2021.3.png)


TEST3
![TEST3] (img/v2021.3.png)


TEST4
![TEST4] (draft/img/v2021.3.png)


TEST5
[[img/v2021.3.png]]


TEST6
[[/img/v2021.3.png]]

TEST7
![TEST7] (/draft/img/v2021.3.png)


TEST7
![TEST7] (jenriquesoriano/draft/release-strategy/img/v2021.3.png)


TEST7
![TEST7] (/jenriquesoriano/draft/release-strategy/img/v2021.3.png)

TEST10
![TEST10] (https://github.com/jenriquesoriano/draft/blob/release-strategy/img/v2021.3.png "v2020.1")

TEST11
![v2020.1](https://github.com/jenriquesoriano/draft/blob/release-strategy/img/v2021.3.png "v2020.1")


















































































