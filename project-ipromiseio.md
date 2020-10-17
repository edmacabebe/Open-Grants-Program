# Open Grant Proposal

* **Project:** ipromiseio
* **Proposer:** Mike Stankavich
* **Payment Address:** 3JnRfeKYYuSTEGKZDbcTKUWMy9NXbuaJKF 

## Project Overview :page_facing_up: 

### Overview

  * A brief description of the project.

    Irrefutable provenance and historical traceability from HR Skillset, food, medicine, dry-goods, etc. is essential in ensuring quality, authenticity, and greater accountability to its management in the supply/value-chain.

    Our work, ipromise.io (pronounced, I promise you) SaaS will be centered on providing a decentralized supply-chain ledger service purposely for irrefutable smart-contract using rust, substrate, FRAME and Ink! The ipromise.io will be consumed by [HireMeLab](www.hiremelab.com) to present a pool of human resources with irrefutable skillsets in rust, substrate, devops and cloud initially just to narrow the scope.
        
  * An indication of how you will integrate this project into Substrate / Polkadot / Kusama.

    Substrate and Ink! will be leveraged as the smart contract ledger that defines the desired properties and conditions. Where these could be deployed to Kusama and Polkadot at its earliest projected verison.

  * An indication of why your team is interested in creating this project.

    The team has been into Horizen Proof of Service [Masternode Managed Service Hosting](www.nodelauncher.com) for the past couple of years and is looking at a way to upgrade/update its knowledge and learn to use newer and more current advancements in Blockchain technology especially on dApps and most specifically DeFi. 

    Our intent eventually, is how we could use web3.0 and PolkaDot as a platform to offer or enable more of our software engineering and DevOps capabilities as a service in a resource pool that could be leveraged by other projects while at the same time build our profile to develop DeFi apps. 

    As our next step (in the short haul), we are also looking at the possibility of developing a multi-cloud IAC deployable Parachain using the Kubernetes platform. And in many ways, enable us to develop more use cases as described below.

  * Other use-cases we are looking at are for DeFi payments, loan, supply-value-chain,
    crowd-funding or mutually pooled funding for Proof-of-Service (masternodes) and Proof-of-Stake (Staking) on managed-service hosted nodes for validators, collators, nominators, fishermen. And of course, for our first use case, we'll focus on building a verfied talent pool for Blockchain-skilled resource.    

### Project Details 
We expect the teams to already have a solid idea about the project's expected final state.

Therefore, we ask the teams to submit (where relevant):
* Mockups/designs of any UI components
  <TODO>

* API specifications of the core functionality
  <TODO>

* An overview of the technology stack to be used
  <TODO>

* Documentation of core components, protocols, architecture etc. to be deployed
  <TODO>

  * System Context Diagram is a high-level view of the interaction between user personas and the the application. 
  
  ![System Context Diagram](./images/SystemContextDiagram.png)
    
  * Architecture Overview is an artifact that rovides an overview of the ‘main conceptual elements and relationships’ of an architecture, which may include candidate subsystems, components, nodes, connections, data stores, users, and external systems. As such, it represents the governing ideas and ‘candidate building blocks’ of the architecture.
  
  ![Architecture Overview](./images/ApplicationArchitecture-ApplicationOverview.png)    
  
* PoC/MVP or other relevant prior work or research on the topic

  There exist an MVP using our [HR App](https://hiremelab.com) that will interface with our substrate-based Blockchain Smart-Contract SaaS ipromise.io that provides a central endpoint to create an Identity, Deploy, Update and View the State.

### Ecosystem Fit 
Are there any other projects similar to yours? If so, how is your project different?
www.litentry.com
## Team :busts_in_silhouette:

### Team members
* Name of team leader: Mike Stankavich
* Names of team members: Edison Macabebe
                         Zoilo dela Cruz 

### Team Website	
* https://ipromise.io
* https://hiremelab.com

### Legal Structure 
Please provide the name and registered address of the legal entity executing the project.

Jackson Peak LLC

### Team's experience

The team has been into providing a Horizen Proof of Service [Masternode Managed Service Hosting](www.nodelauncher.com) for the past couple of years. Here are examples of our commit snips: [1](https://github.com/MikeStankavich/zencash-securenode), and [2]().

### Team Code Repos
* https://github.com/mikestankavich
* https://github.com/edmacabebe
* https://github.com/luxknight007 

### Team LinkedIn Profiles
* https://www.linkedin.com/in/mikestankavich/
* https://www.linkedin.com/in/edison-macabebe-31709b35/
* https://www.linkedin.com/in/zoilodelacruz/

## Development Roadmap :nut_and_bolt: 

This section should break out the development roadmap into a number of milestones. Since the milestones will appear in the grant contract, it helps to describe the functionality we should expect, plus how we can check that such functionality exists in the product. Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions it should be clear how the project is related to Substrate and/or Polkadot. We recommend that the scope of the work can fit within a 3 month period and that teams structure their roadmap as 1 month = 1 milestone. 

For each milestone:
* Please be sure to include a specification of the software. The level of detail must be enough so that we are able to verify that the software meets the specification.
* Please include total amount of funding requested per milestone.
* Please note that we require documentation (e.g. tutorials, API specifications, architecture details) in each milestone. This ensures that the code can be widely used by the community.
* Please provide a test suite, comprising unit and integration tests, along with a guide on how to run these.
* Please commit to providing a dockerfiles for the delivery of your project. 
* Please indicate the milestone duration, as well as number of Full-Time Employees working on each milestone, and include the number of days along with their cost per day.

### Overview
* **Total Estimated Duration:** Duration of the whole project
* **Full-time equivalent (FTE):**  Workload of an employed person ([see](https://en.wikipedia.org/wiki/Full-time_equivalent)) 
* **Total Costs:** Amount of Payment in BTC for the whole project. The total amount of funding needs to be below $30k at the time of submission.

### Milestone 1 Example — Implement Substrate Modules 
* **Estimated Duration:** 1 month
* **FTE:**  2
* **Costs:** 0.8 BTC

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have proper unit-test coverage (e.g. 90%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain |

### Milestone 2 Example — Additional features
...

### Community engagement

As part of the Program, we require that you produce an article/tutorial and publish it (for example on [Medium](https://medium.com/)). It should explain your work done as part of the grant. 

Normally, we ask you to submit the write-up upon the completion of your grant, although for larger projects it might make sense to publish multiple articles after the completion of different milestones.

## Future Plans
Please include the team's long-term plans and intentions.

## Additional Information :heavy_plus_sign: 
Any additional information that you think is relevant to this application that hasn't already been included.

Possible additional information to include:
* What work has been done so far?
* Are there are any teams who have already contributed (financially) to the project?
* Have you applied for other grants so far?
