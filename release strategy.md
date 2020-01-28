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

## ETF Environments
There will be different instances of the ETF deploying different branches of the ATS/ETS/ETF set, with different purposes
* Production instance: stable deployment with official and proven ATS/ETS for the current year's report
* Staging instance: which will contain a pre-publication version of the production
* Beta instance: this environment will contain a version corresponding to the following year's application, so users can choose to validate against the current year's version or the following year's version

## Versioning scheme
For the actual versioning scheme, it is proposed to use a variant of semantic versioning. Since INSPIRE monitoring is on an annual cycle, the year is used as the major version. Minor versions may add relevant changes, while patches may only add fixes that are more lenient.

## Date intervals
It must be kept in mind that the main spirit of this release strategy is to facilitate the reporting to member states, so depending on the time of year, different approaches will be considered for the existing functionalities to be incorporated to the different environments, in accordance with the above.
* [15/01-15/03] Developing new requirements and development of the yearly monitoring tool
* [15/03-15/06] Developing new requirements and development of the yearly monitoring tool
* [15/06-15/09] Incorporating flexibility and lesser stricness in the compliance, if justified
* [15/09-15/01] Providing stability in the yearly reporting environment (bugfixing, performance, etc...) No breaking changes or issues are supossed to be included.

## Types of developments to be considered
Thus, developments to be incorporated in a release have been classified attending to its impact on the production deployment as:

* Breaking changes:
  * Corresponding to an implementation that makes the compliance more restrictive and difficult to pass
  * New tests
* Non-Breaking changes:
  * Implementation reducing restriction for the correct compliance in a requirement
  * Minor changes to the interface that add new functionalities to the interface but it has no effect on the tests
* Hotfix: detected bug that needs to be implemented and extended as soon as possible to the different instances
