There will be different instances of the ETF deploying different branches of the ATS/ETS/ETF set, with different purposes

* Production instance: stable deployment with official and proven ATS/ETS for the current year's report
* Staging instance: which will contain a pre-publication version of the production
* Beta instance: this environment will contain a version corresponding to the following year's application, so users can choose to validate against the current year's version or the following year's version

# Date intervals

It must be kept in mind that the main spirit of this organization is to facilitate reporting to member states, so depending on the time of year, different approaches will be considered for the existing functionalities to be incorporated to the Production instancein each of the environments, in accordance with the above.

* [15/01-15/03] Developing new requirements and development of the yearly monitoring tool
* [15/03-15/06] Developing new requirements and development of the yearly monitoring tool
* [15/06-15/09] Incorporating flexibility and lesser stricness in the compliance, if justified
* [15/09-15/01] Providing stability in the yearly reporting environment (bugfixing, performance, etc...) No breaking changes or issues are supossed to be included.

# Types of developments to be considered

En este sentido, los desarrollos a incorporar se han clasificado de la siguiente forma:

* Breaking changes:
  * Corresponding to an implementation that makes the compliance more restrictive and difficult to pass
  * New tests
* Non-Breaking changes:
  * Implementation reducing restriction for the correct compliance in a requirement
  * Minor changes to the interface that add new functionalities to the interface but it has no effect on the tests
* Hotfix: detected bug that needs to be implemented and extended as soon as possible to the different instances
