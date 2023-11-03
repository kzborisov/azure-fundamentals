# Azure Fundamentals Certification (AZ-900)

This notes will help you prepare for [AZ-900: Microsoft Azure Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-900/) and are based on the official [Microsoft Training](https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/)
(#azure-fundamentals-certification-az-900)

- [Azure Fundamentals Certification (AZ-900)](#azure-fundamentals-certification-az-900)
  - [Part 1. Describe cloud concepts](#part-1-describe-cloud-concepts)
    - [Introduction to cloud computing](#introduction-to-cloud-computing)
      - [What is cloud computing](#what-is-cloud-computing)
      - [Describe the shared responsibility model](#describe-the-shared-responsibility-model)

The `Microsoft Azure Fundamentals` learning part is separated into three parts:

1. Part 1: Describe cloud concepts.
2. Part 2: Describe Azure architecture and services
3. Part 3: Describe Azure management and governance.

The AZ-900 exam includes three knowledge domain areas:

| AZ-900 Domain Area                       | Wight  |
| ---------------------------------------- | ------ |
| Describe cloud concepts                  | 25-30% |
| Describe Azure arhitecture and services  | 35-40% |
| Describe Azure management and governance | 30-35% |

## Part 1. Describe cloud concepts

### Introduction to cloud computing

After learning this you will be able to:

1. Define cloud computing
2. Describe shared responsibility model
3. Define cloud models, including public, private and hybrid
4. Identify appropriate use cases for each cloud model
5. Describe consumption-based model
6. Compare cloud pricing models

#### What is cloud computing

Cloud computing is the delivery of computing services over the internet. This include common IT infrastructure such as:

- virtual machines;
- storage;
- databases;
- networking;

This also include thing like Internet of Things (IoT), machine learning (ML) and artificial inteligence (AI).

Cloud computing is not constrained by physical infrastructure the same way a traditional datacenter is. For example of you increase your IT infrastructure you don't have to build a new datacenter - you can use the cloud to rapidly expand your IT footprint.

With cloud computing you can add or remove compute power and request more storage as you need it. Cloud providers manage the upkeep of the computers so you don't have to.

#### Describe the shared responsibility model

Let's look at a traditional corporate datacenter. The company is responsible for the physical space, security and maintaining or replacing the servers if something happens. The IT department is responsile for maintaining all the infrastructure and software needed to keep the datacenter up and running.

With the `shared responsibility model` these responsibilities get shared between the cloud provider and the consumer.

With an on-premises datacenter you are responsible for everything. With cloud compiting the resposibilities shift. The shared responsibility model is heavily tied into the type of the cloud service (IaaS, Paas, SaaS).

The following diagram highlights how the Shared Responsibility Model informs who is responsible for what, depending on the cloud service type.
![Shared responsibility model](./images/shared-responsibility.svg)

Resposibilities of the cloud provider include:

- physical security
- power
- cooling
- network connectivity

Responsibilities of the consumer are:

- data and information stored on the cloud
- access security
- devices that are allowed to connect to the cloud

Responsibilities determined by the service model:

- operating systems
- network control
- applications
- identity and infrastructure
