# Cloud Computing

## What is Cloud Computing?

Cloud computing is the **on-demand delivery of IT resources over the internet**, usually with **pay-as-you-go pricing**.

Instead of an organization purchasing and maintaining all of its own physical infrastructure, it can obtain computing resources such as:

* Compute
* Storage
* Networking
* Databases
* Applications
* Security services

from a cloud provider when they are needed.

This allows organizations to provision resources quickly without having to build and maintain an entire physical data center themselves.

---

## Benefits of Cloud Computing

### 1. Pay-as-you-go pricing

Cloud providers generally allow customers to pay for the resources they consume instead of making large upfront investments in physical infrastructure.

For example, an organization can provision computing resources when needed and stop paying for resources it no longer uses.

### 2. Scalability

Cloud environments make it easier to increase or decrease resources as demand changes.

An application experiencing a sudden increase in traffic can be scaled to handle additional workload without requiring the organization to purchase new physical servers first.

### 3. Reduced infrastructure management

Organizations do not necessarily need to own and maintain the physical data centers, servers and networking equipment required to provide their applications.

The cloud provider manages the underlying physical infrastructure, while the customer remains responsible for the parts of the environment assigned to them.

### 4. Global accessibility

Cloud services can make applications and resources accessible from different geographical locations through the internet.

Cloud providers operate infrastructure across multiple geographical regions, allowing organizations to deploy applications closer to their users when appropriate.

### 5. Faster provisioning

Cloud resources can typically be provisioned much faster than traditional physical infrastructure.

Instead of waiting to purchase, deliver and install a physical server, an organization can provision a virtual resource through the cloud.

### 6. Flexibility

Organizations can choose from a wide range of computing, storage, networking, database and security services depending on their requirements.

---

# Cloud Service Models

Cloud services are commonly divided into three major service models:

1. **Software as a Service (SaaS)**
2. **Platform as a Service (PaaS)**
3. **Infrastructure as a Service (IaaS)**

The major difference between them is **how much of the technology stack the cloud provider manages**.

```text
                    MORE CUSTOMER CONTROL
                            ▲
                            │
                         IaaS
                            │
                         PaaS
                            │
                         SaaS
                            │
                            ▼
                   MORE PROVIDER MANAGEMENT
```

## Software as a Service (SaaS)

SaaS provides users with a complete software application through the internet.

The cloud provider manages most of the underlying infrastructure and application environment.

The customer primarily interacts with the application rather than managing servers or operating systems.

**Examples include:**

* Email applications
* Collaboration platforms
* File-sharing applications
* Customer relationship management software

### Simple example

Instead of installing and maintaining an email server yourself, you can use a cloud-based email service.

---

## Platform as a Service (PaaS)

PaaS provides developers with an environment for building, testing and deploying applications without requiring them to manage most of the underlying infrastructure.

The provider manages components such as the underlying servers and operating environment, allowing developers to focus more on their application.

### Simple example

A developer can deploy an application to a managed platform without having to manually configure the physical servers on which the application runs.

---

## Infrastructure as a Service (IaaS)

IaaS provides fundamental computing infrastructure such as:

* Virtual machines
* Storage
* Networking
* Other infrastructure resources

IaaS generally provides customers with more control than SaaS or PaaS.

For example, with an infrastructure service such as Amazon EC2, a customer can configure the operating system, networking and applications running on the virtual machine.

---

# Cloud Deployment Models

Cloud deployment describes **where and how an organization's infrastructure is hosted and managed**.

The three deployment approaches covered here are:

1. **Cloud-based**
2. **On-premises**
3. **Hybrid**

---

## Cloud-Based Deployment

In a cloud-based deployment, an organization runs its applications and infrastructure using cloud resources.

An organization may either:

* migrate existing applications and data to the cloud, or
* build new applications directly in the cloud.

The organization and cloud provider have different responsibilities for securing and managing the environment.

This leads to the concept of the **shared responsibility model**.

---

## On-Premises Deployment

In an on-premises environment, an organization operates its infrastructure within facilities that it controls.

The organization is responsible for managing components such as:

* Physical servers
* Networking equipment
* Storage
* Data center facilities
* Operating systems
* Applications
* Security controls

Organizations may choose on-premises infrastructure because of factors such as regulatory requirements, existing investments, data-control requirements or organizational policies.

---

## Hybrid Deployment

A hybrid environment combines **on-premises infrastructure with cloud resources**.

For example, an organization could keep certain sensitive workloads within its own infrastructure while using cloud services for workloads that require additional scalability.

```text
                 HYBRID ENVIRONMENT

        ┌───────────────────────┐
        │     ON-PREMISES       │
        │                       │
        │  Servers              │
        │  Sensitive workloads  │
        │  Internal systems     │
        └───────────┬───────────┘
                    │
                 Network
                    │
        ┌───────────▼───────────┐
        │         CLOUD         │
        │                       │
        │  Scalable workloads   │
        │  Cloud services       │
        │  Additional resources │
        └───────────────────────┘
```

Hybrid environments can allow organizations to combine the control of on-premises infrastructure with the scalability and flexibility of cloud services.

---

# Why This Matters for Cloud Security

Understanding cloud computing fundamentals is important before learning cloud security.

Security decisions depend on understanding **where resources exist, who manages them and who is responsible for securing each component**.

For example:

* With SaaS, the provider manages most of the underlying infrastructure.
* With PaaS, the provider manages the platform while the customer focuses on their application and data.
* With IaaS, the customer has greater responsibility for configuring and securing their environment.

This is why understanding the **shared responsibility model** is fundamental to cloud security.

---

## Key Takeaways

* Cloud computing provides IT resources on demand over the internet.
* Cloud environments can reduce the need for organizations to maintain their own physical infrastructure.
* Cloud resources can be scaled according to demand.
* SaaS, PaaS and IaaS are **cloud service models**.
* Cloud-based, on-premises and hybrid describe different **deployment approaches**.
* The amount of responsibility shared between the cloud provider and customer depends on the service being used.
* Understanding cloud fundamentals is the foundation for learning cloud security.

