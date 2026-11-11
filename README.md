# Khalid Ouhmid

Cloud & AI engineer (apprentice) at Safran Helicopter Engines. Engineering student at Efrei.

I work on AWS infrastructure, CI/CD shared across many repositories, and LLM agents that operate on infrastructure code. Most of what I build is tooling for other engineers.

## Keelson

[**Keelson**](https://github.com/khalidOuhmid/keelson) is an open source tool that reads your existing GitLab CI and GitHub Actions files, maps each job to the [OWASP DevSecOps Guideline](https://owasp.org/www-project-devsecops-guideline/), shows which layers are missing, and writes the fix back into your YAML.

[![Keelson demo](https://github.com/khalidOuhmid/keelson/raw/main/docs/demo/keelson.gif)](https://github.com/khalidOuhmid/keelson)

What I spent the most time on:

- **Lossless editing.** Files are parsed to a concrete syntax tree and edited as byte-level patches, each with an exact inverse. Parse then emit with no change is byte-identical: comments, key order and anchors survive.
- **Computed coverage.** 13 OWASP layers and 8 platform categories, detected from what jobs actually run (images, scripts, actions) against a catalogue of 62 tools.
- **Fleet edits.** Every change is a serialisable operation, so it can be reviewed once and replayed across many repositories, all or nothing per repository.
- **Testing.** Property tests on round-trip, invertibility and edit locality over official GitLab templates and GitHub starter workflows, plus Playwright on the built binary.

TypeScript, Bun, React. Apache-2.0. Version 0.1.0 runs from source; the npm release is next.

## At work

- Created and maintain the shared GitLab CI/CD component catalogue used by 1,400+ repositories.
- Review Terraform and AWS merge requests with the DevOps and sysadmin teams every week.
- Build agent-based tooling for infrastructure code.

## Stack

TypeScript · Python · AWS · Terraform · GitLab CI · GitHub Actions · Docker · React

## Contact

[LinkedIn](https://www.linkedin.com/in/khalid-ouhmid-062830329/) · [khalidouhmid.com](https://khalidouhmid.com) · [khalidouhmid.pro@gmail.com](mailto:khalidouhmid.pro@gmail.com)
