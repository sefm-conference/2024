---
layout: page
title: Artifacts
permalink: /artifacts/
order: 6
published: false
---

This year, SEFM includes an artifact evaluation performed by the artifact evaluation committee (AEC). The artifact evaluation serves to enable future researchers to effectively build on and compare with previous work. We will be attributing 3 badges, according to the [EAPLS badging scheme](https://eapls.org/pages/artifact_badges/):

1. Artefact **functional**: documented, consistent, complete, exercisable;
2. Artefact **reusable**: exceeding functional, by being carefully documented and well-structured for reuse and repurposing, see below for details;
3. Artefact **available**: available on a publicly accessible archival repository to a permanent repository that provides a Digital Object Identifier (DOI).

**Tool papers** must be accompanied by an artifact. This artifact should at least meet the requirements for the **functional badge** for the paper to be eligible for acceptance.  
 Authors of **regular papers** are not required to have an accompanied artifact but are however welcome to submit one for evaluation.

## Important Dates

- Artefact submission for **tool papers** : ~~9 June 2023~~ **30 June 2023**
- Artefact submission for **regular papers** : ~~16 June 2023~~ **30 June 2023**
- Author notification: 18th of August 2023

All deadlines are AoE.

## Artifact Submission Guidelines

Submission site: [https://easychair.org/conferences/?conf=sefm2023](https://easychair.org/conferences/?conf=sefm2023) under the SEFM2023-ARTEFACTS Track.

Artifact submission should consist of the following:

- An **abstract** containing:
  - a summary of the artifact and explanation of its relation to the paper,
  - a URL from which a **.zip** file containing the artifact can be downloaded,
  - the **SHA256** checksum of the .zip file upon submission,
  - if applicable, a description of any additional special requirements beyond a VM or Docker image needed to properly run the artifact, e.g. cloud-computing resources, certain hardware, and,
  - an explanation as to why you should qualify for a reusable badge.
- The paper submission ID of your submitted paper.
- A **.pdf** file of the submitted paper.

## Checksum instructions

When uploading your artifact to the URL, please update the  **SHA256**  checksum of the .zip file in the abstract. You can generate the checksum using the following command-line tools.

- Linux: `sha256sum`
- Windows: `CertUtil -hashfile SHA256`
- MacOS: `shasum -a 256`

## Packaging Guidelines

The linked **.zip** file must contain the following:

- The artifact, i.e., data, software, libraries, scripts, etc. required to replicate the results of your paper. Please prepare a **Docker image** or a **Virtual Machine**. We recommend to use VirtualBox to save a VM image as an **OVA file**.
- A **LICENSE** file containing a license for your artifact. Your license must allow the artifact evaluation committee members to download and evaluate the artifact, e.g., download, use, execute, and modify the artifact for the purpose of artifact evaluation. Please refer to typical open-source licenses. Artifacts without an open-source license are also accepted, but a license type needs to be specified, allowing the committee to assess the artifact. For quick help about possible licenses, visit [https://choosealicense.com/](https://choosealicense.com/).
- A **README** file that introduces the artifact to the user and guides the user through the replication of your results. Ideally, it should consist of the following parts:
  - Any additional requirements for running the artifact, such as hardware requirements or additional proprietary software;
  - The expected total runtime to run the experiments;
  - Detailed and specific reproducibility instructions to set up and use the artifact to replicate the results in the paper; including an explanation of which claims and results cannot be replicated and why.
- **Note**: Experiments that require a large amount of runtime, i.e. more than 2 hours, or memory, i.e. more than 4 GB, should supply a small subset of their experiment that can be run within these bounds.

If you cannot submit the artifact as requested or encounter any other difficulties in the submission process, please contact the artifact evaluation chairs prior to submission.

## Contact

Mário Periera [mjp.periera@fct.unl.pt](mailto:mjp.periera@fct.unl.pt)  
Flip van Spaendonck [p.h.m.v.spaendonck@tue.nl](mailto:p.h.m.v.spaendonck@tue.nl)
