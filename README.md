# Roadmap
## Process and Tools
The Notary v2 team uses the [Roadmap GitHub Project Board](https://github.com/notaryproject/roadmap/projects/1) to track short term (1-3 months) and medium term (3-6 months) efforts and long term (6-12 months). Once a broad objective (from the "Future/Backlog" column) is further scoped into a GitHub issue that has a clear objective, background and motive, it is moved into the "To do" column. From there, the Notary v2 team plans its releases via [GitHub Milestones](https://github.com/notaryproject/roadmap/milestones).

## Current and Future Objectives
At this time, the Notary community is working on Notary v2 specification  and two separate sub projects, TUF and Notation. This roadmap is focused  on the Notary v2 specification and its reference implementation in Notation client

### Current (Short term) Focus
- Collaborate with other open source projects for co-related/dependent features needed for signature verification with other open source clients


### Future (Mid to Long term) Focus
- Iterate on the Notary v2 specification and Notation client based on community feedback
- Add Revocation support in the Notation Client

### Leading up to the first stable release
*The following milestones lead up to the first release. During alpha and beta milestones, backwards compatibility is not guaranteed.  Refer release definitions [here](https://github.com/notaryproject/notation/blob/main/RELEASE_MANAGEMENT.md). Test cases will be added along the way. After RC-1 backward compatibility will be maintained*
- [alpha-1](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3Aalpha-1) [Release Notes](https://github.com/notaryproject/roadmap/blob/main/RELEASENOTES/v2.0.0.alpha-1.MD): Goal - Get feedback on the notation CLI client and notation user experience
- [alpha-2](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3Aalpha-2) [Release Notes](https://github.com/notaryproject/roadmap/blob/main/RELEASENOTES/v2.0.0.alpha-2.MD): Goal - Merge open PR on the Notaryv2 standard, CLI and Notation specifications 
- [alpha-3](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3Aalpha-3) [Release Notes](https://github.com/notaryproject/roadmap/blob/main/RELEASENOTES/v2.0.0.alpha-3.MD): Goal - Introduce Plugins for signing and verification. Manage signatures in OCI registries using [ORAS Artifacts Specification v1.0.0-RC.2](https://github.com/oras-project/artifacts-spec/releases/tag/v1.0.0-rc.2)
- [alpha-4](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3Aalpha-4) [Release Notes](https://github.com/notaryproject/roadmap/blob/main/RELEASENOTES/v2.0.0.alpha-4.MD): Goal - Add COSE signature format 
- [beta-1](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3ABeta-1)   [Release Notes](https://github.com/notaryproject/roadmap/blob/main/RELEASENOTES/v2.0.0.beta-1.MD): Goal - Verify using Trust Store and Trust Policy 
- [RC-1](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3ARC-1)       [Release Notes](https://github.com/notaryproject/roadmap/blob/main/RELEASENOTES/v2.0.0.rc-1.MD)): Goal -First supported release from Notary v2 community. JWS and COSE signature formats. Notation CLI client 
- [RC-2](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3ARC-2)       [Release Notes](https://github.com/notaryproject/roadmap/blob/main/RELEASENOTES/v2.0.0.rc-2.MD)): Goal - Support "Fallback" method for OCI 1.0 based registries to manage signatures 
- [RC-3](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=milestone%3ARC-3)       [TBD] 

| Repo | Related High-Level Roadmap items for above milestones  | Repo level project board (*filter based on milestones as you need them*)  |
|------|-----------------------------------------------------------|--------------------------------------------------|
|[Notaryproject](https://github.com/notaryproject/notaryproject)| [Issues labeled with "notaryproject"](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=label%3Anotaryproject) | [From all repos](https://github.com/orgs/notaryproject/projects/10)|
|[Notation](https://github.com/notaryproject/notation)| [Issues labeled with "notation-CLI"](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=label%3Anotation-CLI) | [From all repos](https://github.com/orgs/notaryproject/projects/10)|
|[Notation-go](https://github.com/notaryproject/notation-go)| [Issues labeled with "notation-API"](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=label%3Anotation-API) | [From all repos](https://github.com/orgs/notaryproject/projects/10)|
|[Notation-core-go](https://github.com/notaryproject/notation-core-go)| [Issues labeled with "notation-API"](https://github.com/iamsamirzon/roadmap/projects/1?card_filter_query=label%3Anotation-API) | [From all repos](https://github.com/orgs/notaryproject/projects/10)|
| Consolidated View  | [Roadmap milestones across all repos](https://github.com/iamsamirzon/roadmap/projects/1) | [From all repos](https://github.com/orgs/notaryproject/projects/10) |

## Getting Involved

Please file [GitHub issues](https://github.com/notaryproject/notaryproject/issues) to propose features and identify bugs. See more information about how to get involved with the community [here](https://github.com/notaryproject).
