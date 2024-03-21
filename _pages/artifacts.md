---
layout: page
title: Artifacts
permalink: /artifacts/
order: 6
published: false
---
# Call for Artifacts
Claims and (experimental) results described in a paper often originate from artifacts not present in the paper. Reproducibility of (experimental) results is crucial to foster an atmosphere of open, reusable, and trustworthy research. Furthermore, good artifacts enable future researchers to effectively build on and compare with previous work.

Similar to last year, SEFM includes artifact evaluation, which is performed by a separate artifact evaluation committee (AEC). Artifact evaluation is **mandatory for tool papers** and **optional for regular papers**. The goals of artifact evaluation are to encourage authors to provide artifacts for replication and future use and to reward authors who create good artifacts. 

Artifacts of interest include (but are not limited to):
-	Software, Tools, or Frameworks
-	Data sets
-	Test suites
-	Machine-checkable proofs
-	Any combination of them
-	Any other artifact described in the paper

We aim to assess the artifacts themselves and not the quality of the research linked to the artifact, which is assessed by the SEFM 2024 program committee. However, **artifacts for tool papers** should at least meet the requirements for the **functional badge** for the paper to be eligible for acceptance.

## Important Dates
-	Artifact submission deadline: June 30th, 2024 (AOE)
-	Test phase notification: July 12th, 2024
-	Author respond period: July 12th-July 18th, 2024 (AOE)
-	Artifact notification: August 15th, 2024

## Awarded Badges
SEFM awards the [Artifacts Available and Artifacts Evaluated badges of EAPLS](https://eapls.org/pages/artifact_badges/).
1.	The Artifacts Evaluated badge has two levels, functional and reusable. We will award at most one of the two levels.
    1.	For the artifacts **functional** badge, the artifact must be documented, consistent, complete, and exercisable.
    2.	For the artifacts **reusable** badge, the artifact must meet the requirements of the artifacts functional badge and in addition must be of very high quality, i.e., it is also carefully documented and well-structured for reuse and repurposing.
2.	The artifacts **available** badge will be awarded if the artifact is **publicly and permanently available** via a Digital Object Identifier (**DOI**) that is referenced in the respective paper and the artifact is **relevant** for the paper and adds **value** beyond the paper.

The Artifacts Available badge and Artifacts Evaluated badge are awarded independently of each other. Artifacts that are not exercisable, as, for example, protocols used for empirical studies, will be evaluated only according to the Available badge, as the Evaluated badges are not applicable to them. All awarded badges will be shown on the first page of the paper.

## Artifact Submission
An artifact submission should consist of
-	an **abstract** that
    *	summarizes the artifact and explains its relation to the paper,
    *	mentions where in the artifact it is documented how to perform the test phase and how to reproduce the results of the paper, 
    * if applicable, provides a description of any **additional special requirements** beyond a VM or Docker image needed to properly run the artifact, e.g. cloud-computing resources, certain hardware,
    * includes an **URL** - we encourage you to provide a DOI - to a **.zip** file of your artifact containing 
        +	a **license** file that allows the artifact evaluation committee to evaluate the artifact,
        + a clear **documentation** how to perform the **test phase**, and
        + a **documentation how to reproduce the results** of the paper,
    * the **SHA256 checksum** of the .zip file, and
    *	the **paper submission ID** of your submitted paper.
-	a **.pdf** file of the submitted paper. For the availability badge, the paper must reference the DOI of your artifact.

Please consider the [Artifact Packaging Guidelines](#artifact-packaging-guidelines) for detailed information about the contents of the artifact.

The abstract and the .pdf file of your paper must be submitted via EasyChair.

If you cannot submit the artifact as requested or encounter any other difficulties in the submission process, please contact the artifact evaluation chair prior to submission. 

## Artifact Packaging Guidelines

### Checksum instructions
We need the checksum to ensure the integrity of your artifact. You can generate the checksum using the following command-line tools. 

- Linux: `sha256sum <file>`
- Windows: `CertUtil -hashfile <file> SHA256`
- MacOS: `shasum -a 256 <file>`


## Artifact Evaluation Process and Criteria
We aim to assess the artifacts themselves and not the quality of the research linked to the artifact, which is assessed by the SEFM 2024 program committee. The goal of our review process is to be constructive and to improve the submitted artifacts. Only, if an artifact cannot be improved to achieve sufficient quality in the given time frame or it is inconsistent with the paper, it should be rejected.

All artifacts are evaluated by the artifact evaluation committee. Each artifact will be reviewed by at least two committee members. Reviewers will read the accepted paper and explore the artifact to evaluate how well the artifact supports the claims and results of the paper. The evaluation is based on the following questions:
*	Is the artifact consistent with the paper and the claims made by the paper, e.g., does it significantly contribute to the generation of its main results?
*	Is the artifact complete, i.e., how many of the results of the paper are replicable?
* Are the results of the paper replicable through the artifact, e.g., can the included software be used to generate the results of the paper and included data be accessed and manipulated?
* Is the artifact well-documented?
* Is the artifact easy to use?
* Does the artifact provide a proper and explicitly documented license?
* Is the artifact publicly and permanently available?
* Is a DOI to the artifact provided and referenced in the paper?
* Is the artifact relevant for the associated paper and does it provide additional value?

The artifact evaluation is performed in the following two phases.
1.	**Test Phase**: Reviewers **check if the artifact is functional**, i.e., they look for setup problems (e.g., corrupted, missing files, crashes on simple examples, etc.). The authors are informed of the outcome of the test phase by the **test phase notification** deadline. If any problems are detected during the test phase, the authors are asked to **solve the problems** and answer the respective issue until the end of the **author respond period**. If no problems were detected, the reviewers will continue with the assessment phase directly after the test phase notification.
2.	**Assessment Phase**: In the assessment phase, reviewers will try to **reproduce** any experiments or activities and **evaluate** the artifact w.r.t the questions detailed above. The final review is communicated together with the awarded badges in the artifact notification.

## Artifact Evaluation Chair
[Marie-Christine Jakobs](https://www.sosy-lab.org/people/jakobs/), LMU Munich
