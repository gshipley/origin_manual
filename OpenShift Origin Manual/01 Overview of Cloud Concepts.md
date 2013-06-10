#1 Overview of Cloud Concepts

##**1.1 Cloud Terms and Definitions**

The National Institute of Standards and Technology [NIST](http://nist.gov) defines Cloud Computing in [Special Publication 800-145](http://csrc.nist.gov/publications/nistpubs/800-145/SP800-145.pdf)

> Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction.
> This cloud model is composed of five essential characteristics, three service models, and four deployment models.

The three Cloud Service Models are:
1.  Infrastructure as a Service (IaaS)
2.  Platform as a Service (PaaS)
3.  Software as a Service (SaaS)

These models can be deployed according to a number of archetypes -- the Cloud Deployment Models:
1.  Public Cloud
2.  Community Cloud
3.  Private Cloud
4.  Hybrid Cloud

Understanding of the Cloud Service Models and Deployment Models is essential in order to understand OpenShift's scope and architecture.

##**1.2 Historical Perspective**

The Platform as a Service model is rapidly changing the fundamental way in which developers do what they do -- write software.  In the legacy development paradigm, developers depended on systems administrators to procure, provision, and maintain their development and production environments.  The system administrators would be responsible for hardening, configuring, and patching these environments.  This was a lengthy and ongoing process that produced unnecessary drag on the developers.

In order to avoid some of that "infrastructure drag," developers would typically use local sandboxes.  For example, a developer might start JBoss locally, then deploy a .war or .ear file into a local directory.  This process did not at all mirror the production deployment process, and the learning curve produced even more drag.

##**1.3 The PaaS Revolution**

The Platform as a Service model changes everything.  Now a developer can focus on development.  Infrastructure details are abstracted, deployments are consistent across environments, and the time that would have been spent dealing with drag can be used to innovate.


##**1.4 OpenShift Infrastructure Options**

OpenShift Origin is infrastructure agnostic -- it can be deployed on bare metal; private virtualization stacks like VMware or RHEV; and any IaaS cloud instance such as EC2, Rackspace, OpenStack, or CloudStack.  All that is required is an underlying x86_64 operating system (OS) that is Red Hat Enterprise Linux (RHEL) based, such as Fedora.  This will guarantee that enterprise features like SELinux will be supportable, reliable, and secure.
