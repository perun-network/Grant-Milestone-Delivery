# Milestone Delivery :mailbox:

> ⚡ Only the GitHub account, which is responsible for the pull request of the accepted application is allowed to submit milestones. 
> 
> Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with `>`, such as this one, can be removed.

> //TODO fill form

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/General-Grants-Program/blob/master/grants/milestone-deliverables-guidelines.md).**

* **Application Document:** https://github.com/w3f/Grants-Program/blob/master/applications/perun_channels.md
* **Milestone Number:** 1

> Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work. 
> 
> If there is anything particular about any of the deliverables we or a future reader should know, use the respective `Notes` column.

> //TODO check links and notes

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 0a. | License | [Apache 2.0](https://github.com/perun-network/perun-polkadot-pallet/tree/milestone1/LICENSE) | |
| 0b. | Documentation | [README](https://github.com/perun-network/perun-polkadot-pallet/tree/milestone1/README.md#documentation) | We provide in-code docs and an architecture overview in the README. |
| 0c. | Testing Guide | [README](https://github.com/perun-network/perun-polkadot-pallet/tree/milestone1/README.md#tests) | Have a look at the [repo structure](https://github.com/perun-network/perun-polkadot-pallet/tree/milestone1/README.md#repo-structure) to find all test files. |
| 0d. | Docker | [Dockerfile](https://github.com/perun-network/perun-polkadot-pallet/tree/milestone1/Dockerfile) and [docker-compose.yml](https://github.com/perun-network/perun-polkadot-node/tree/milestone1/docker-compose.yml) | The dockerfile is for testing and the compose is for setup + tryout. |
| 1. | Setup | [Setup repo](https://github.com/perun-network/perun-polkadot-node/tree/milestone1/) | The setup repo shows how to use the Perun pallet. **//TODO clarify with OTY how we should include the node repo. The Setup task was just meant to cover the setup of the pallet repository.** |
| 2. | Core Types | [types.rs](https://github.com/perun-network/perun-polkadot-pallet/tree/milestone1/src/types.rs) | *Params*, *State*, *RegisteredState* and *Whithdrawal* |
| 3. | Deposit | [lib.rs](https://github.com/perun-network/perun-polkadot-pallet/tree/milestone1/src/lib.rs#L213) |  |

