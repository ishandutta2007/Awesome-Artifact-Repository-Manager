# Awesome-Artifact-Repository-Manager

## Top Artifact Repository Manager Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Package Registries, Container Registries, Binary Repositories, Proxy/Cache & Software Supply-Chain Artifact Storage*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Artifact Repository Managers**. These systems store, version, proxy, and secure build outputs—Maven/npm/PyPI packages, container images, Helm charts, and generic binaries—for CI/CD and runtime consumption.



**Examples** include JFrog Artifactory, Sonatype Nexus, Cloudsmith, Azure Artifacts, GitHub Packages, Google Artifact Registry, AWS CodeArtifact, ProGet, Harbor, Packagecloud/Gemfury, and GitLab Package Registry (the category leaders).



**Open-source emphasis**: Strong open options exist. **Harbor**, **Nexus Repository OSS**, **Artifact Keeper**, and format-specific registries (Verdaccio, etc.) cover most self-hosted needs. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[JFrog Artifactory](https://jfrog.com/artifactory/)**  

  Universal artifact repository—proxy, host, and promote packages and images across many formats with rich enterprise features.



- **[Sonatype Nexus Repository](https://www.sonatype.com/products/nexus-repository)**  

  Widely used repository manager for Maven and many other formats; OSS and Pro editions.



- **[Cloudsmith, Packagecloud, Gemfury](https://cloudsmith.com/)**  

  Managed multi-format package hosting with strong distribution and access-control features.



- **[Azure Artifacts, AWS CodeArtifact, Google Artifact Registry, GitHub Packages, GitLab Package Registry](https://azure.microsoft.com/products/devops/artifacts)**  

  Cloud-native artifact registries integrated with major DevOps and cloud platforms.



- **[ProGet (Inedo)](https://inedo.com/proget)**  

  Universal package server with free and enterprise editions for private feeds and promotion pipelines.



- **[Harbor (as a product / support offerings)](https://goharbor.io/)**  

  CNCF container and OCI artifact registry—often self-hosted; commercial support available.



- **[Other commercial artifact platforms](https://jfrog.com/artifactory/)**  

  Additional universal and specialty package registries.



## Open-Source GitHub Projects



- **[Harbor](https://github.com/goharbor/harbor)**  

  Leading open-source (Apache 2.0) cloud-native registry—OCI images and artifacts, RBAC, vulnerability scanning, replication, and signing; CNCF project.



- **[Nexus Repository OSS](https://github.com/sonatype/nexus-public)**  

  Open-source edition of Sonatype Nexus—Maven and other repository formats for private and proxy repositories.



- **[Artifact Keeper](https://github.com/artifact-keeper/artifact-keeper)**  

  Emerging open-source universal artifact registry—many package formats, scanning, and self-hosted deployment aimed at Artifactory/Nexus alternatives.



- **[Verdaccio](https://github.com/verdaccio/verdaccio)**  

  Lightweight open-source private npm registry—popular for Node.js teams needing a simple private feed.



- **[Distribution (CNCF/Docker Registry)](https://github.com/distribution/distribution)**  

  Reference open-source OCI/Docker registry implementation underlying many private image registries.



- **[Forgejo/Gitea packages, GitLab CE registry](https://github.com/go-gitea/gitea)**  

  Open Git forges that include built-in package and container registries for smaller teams.



- **[Pulp](https://github.com/pulp/pulpcore)**  

  Open content repository platform used for RPM and other enterprise package types.



- **[Bag-specific registries (PyPI, NuGet, etc.)](https://github.com/pypiserver/pypiserver)**  

  Simple open servers for individual ecosystems when a universal manager is unnecessary.



### Additional Strong Open-Source Options



- **Containers/OCI**: Harbor as the standard secure open registry.

- **Maven/Java**: Nexus OSS.

- **npm**: Verdaccio.

- **Universal aspirants**: Artifact Keeper and similar projects.

- **Composable stacks**: CI publish → Harbor/Nexus/Verdaccio → admission controllers / SCA scanning.

- Commercial platforms still lead in multi-format enterprise features, support, and SaaS convenience.



**Frameworks for building custom systems**:  

**Harbor** for containers; **Nexus OSS** for Maven and mixed formats; **Verdaccio** for npm.  

Commercial registries (Artifactory, Nexus Pro, Cloudsmith, cloud provider registries) add promotion, edge caching, and SLAs.  

Many teams self-host Harbor + Nexus OSS and use cloud registries for public or multi-region distribution. Fully open stacks are production-viable for most internal artifact needs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Artifact repositories are critical to the software supply chain. Enforce authentication, signing, vulnerability scanning, and immutability where required. Compromised registries can distribute malware to entire organizations.

- Open-source registries offer control and cost savings but require hardened deployment, backups, and upgrades. Commercial platforms shift operational burden to the vendor. Align registry practice with your security and compliance requirements.



---



**Made for platform engineers, DevOps teams, and anyone securing the path from build to runtime.**  

Let's expand open artifact management while recognizing the format coverage and enterprise features that leading commercial repository platforms deliver.
