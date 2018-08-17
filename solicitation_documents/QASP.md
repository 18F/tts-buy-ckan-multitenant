**General Services Administration**

Federal Acquisition Service

Technology Transformation Services

1800 F St NW | Washington, DC | 20405

**Office of Products and Programs  
**Data.gov Multi-Tenant CKAN Development Support

**Quality Assurance Surveillance Plan**

# **Introduction**

The General Services Administration (GSA) Technology Transformation
Services (TTS) has developed this Quality Assurance Surveillance Plan
(QASP) to evaluate contractor actions while implementing the Performance
Work Statement (PWS). It is designed to provide an effective
surveillance method of monitoring contractor performance for each listed
task in the Requirements section in the Task Order (TO). It also
provides a systematic method to evaluate the services the contractor is
required to furnish.

# **Standard**

The Contractor is responsible for management and quality control actions
to meet the terms of the TO. The Contractor shall perform all work
required in a satisfactory manner in accordance with the requirements of
the PWS. The Contracting Officer's Representative (COR) shall notify the
Contracting Officer (CO) for appropriate action if it is likely that the
Contractor will not achieve successful final delivery of the software
code in accordance with the performance standards and acceptable quality
levels identified below.

# **The CO’s responsibilities**

The CO is responsible for monitoring contract compliance, contract
administration, and cost control and for resolving any differences
between the observations documented by the COR and the Contractor. The
CO will designate a COR as the Government authority for performance
management. The number of additional representatives serving as
technical inspectors depends on the complexity of the services measured,
as well as the Contractor’s performance, and must be identified and
designated by the CO.

# **The COR’s responsibilities**

The Contracting Officer’s Representative (COR) is designated in writing
by the CO to act as his or her authorized representative to assist in
administering a contract. COR limitations are contained in the written
appointment letter. The COR is responsible for technical administration
of the project and ensures proper Government surveillance of the
Contractor’s performance. The COR is not empowered to make any
contractual commitments or to authorize any contractual changes on the
Government’s behalf. Any changes that the Contractor deems may affect
contract price, terms, or conditions shall be referred to the CO for
action. The COR will have the responsibility for completing QA
monitoring forms used to document the inspection and evaluation of the
Contractor’s work performance. Government surveillance may occur under
the inspection of services clause for any service relating to the
contract.

# **Performance Requirements Summary**

The COR will evaluate the performance standards through surveillance as
reflected below by reviews and acceptance of work products and services.
As indicated, the COR will assess progress towards the final delivered
software code. The performance requirements listed below are required
for every sprint to enable incremental delivery of code. Code will be
assessed by the Government to ensure that the contractor is on a path to
successful final
delivery.

##

| **Characteristic** | **Performance Standard(s)**                                                                                                                                          | **Acceptable Quality Level**                                                                                                                                                   | **Method of Surveillance**                                                                                                        |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| Tested Code        | Code delivered under the order must have comprehensive test code coverage and a clean code base.                                                                     | Test coverage for all developed code, including all integration and acceptance tests and any new tests that may be needed. All code to be tested under continuous integration. | Combination of manual review and the results of automated testing by Government personnel (TTS).                                  |
| Accepted           | Functions agreed upon as done for a given issue in the Data.gov GitHub repository created for the Task Order.                                                        | All functions appear and operate as expected.                                                                                                                                  | Manual review of Government personnel (TTS) for user-facing features and bugs.                                                    |
| Deployable         | Code must be successfully built and deployed into staging environment and configurable for the production environment.                                               | Successful build and repeatable idempotent deployments.                                                                                                                        | Combination of manual review and automatic testing by Government personnel (TTS).                                                 |
| Documentation      | All dependencies are listed and documented. Major functionality in the software/source code is documented. System diagram is provided as appropriate to the release. | In order to meet TTS needs as agreed to following initial releases with the Product Owner, COR, and CO.                                                                        | Combination of manual review and automatic testing, if available, by Government personnel (TTS).                                  |
| Security           | Open Web Application Security Project (OWASP) Application Security Verification Standard 4.0.                                                                        | Code developed and/or used from a third party must be free of high or critical level static and dynamic security vulnerabilities.                                              | Clean results from tests as defined by Data.gov PMO and GSA IT Security, along with documentation explaining any false positives. |

If any deliverables produced by the contractor during performance fail
the quality levels provided above, the contractor will correct those
deliverables to meet the specified quality level at no extra cost to the
Government.
