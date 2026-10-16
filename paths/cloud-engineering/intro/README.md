# Introduction to cloud engineering

Cloud engineering is the work of planning, setting up, and maintaining computing services over a network. Instead of owning every computer involved, a team can use services from a cloud provider and pay according to the service's terms.

## Core concepts

| Concept | Plain meaning |
| --- | --- |
| Compute | Processing power that runs programs, such as a virtual machine: a software-based computer. |
| Storage | A place to keep files and other data. |
| Networking | Connections that let computers and services communicate. |
| Deployment | Putting an application or service where it can run. |
| Public cloud | Services supplied by a provider to customers. Public does not mean your files must be public. |
| Private cloud | Cloud infrastructure dedicated to one organization. |
| Hybrid cloud | A setup combining private infrastructure with public cloud services. |

## Choosing a first provider

1. Think about a class, project, or job goal that interests you.
2. Compare the providers below and choose one with learning material that fits that goal. There is no single best provider for everyone.
3. Begin with free reading. If a later exercise asks for a cloud account, review its pricing and cleanup instructions before creating services. A free lesson does not guarantee free service usage.
4. Draw a simple study website with a place to run it, a place to keep files, and a connection between them. Label which parts are compute, storage, and networking.

| Provider | Company | Example names you may meet | This kit |
| --- | --- | --- | --- |
| [Azure](../microsoft-azure/README.md) | Microsoft | Virtual Machines for compute; Blob Storage for files | Available fundamentals route |
| [Google Cloud Platform](../google-cloud-platform/README.md) | Google | Compute Engine for compute; Cloud Storage for files | Available fundamentals route |
| [AWS](../aws/README.md) | Amazon | EC2 for compute; S3 for files | Available fundamentals route |

All three offer compute, storage, and networking. Their names, account setup, and prices differ. Official documentation is linked in each provider's resources file.

## Fundamentals first, then a role

These are entry-level credentials for understanding cloud ideas. They cover different material and are not interchangeable engineering qualifications. None replaces practice, and taking all three exams is not required.

| Provider | Fundamentals starting point | Emphasis |
| --- | --- | --- |
| Microsoft Azure | [Azure Fundamentals: AZ-900](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/) | Cloud concepts and Azure services and management |
| AWS | [Cloud Practitioner: CLF-C02](https://docs.aws.amazon.com/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.html) | Broad AWS concepts, responsibilities, services, and costs |
| Google Cloud | [Cloud Digital Leader](https://cloud.google.com/learn/certification/cloud-digital-leader) | Cloud concepts and business use cases, including data and AI |

AI means artificial intelligence: systems that perform tasks such as recognizing patterns. AWS's exam code is CLF-C02, with a zero. This kit keeps Google Cloud in `google-cloud-platform/`; GCP is its abbreviation, not a second folder.

1. Choose one provider and follow its roadmap from foundations to a small project. Start with free reading; a paid exam is optional.
2. Use the current official exam guide if certification is your goal. Names and references were checked on 2026-10-16, but requirements can change.
3. Add practical foundations beyond the exam: operating systems, networking, Git (file-change tracking), and simple scripts (code for repeatable tasks).
4. Choose one role direction below and identify a next practice task. Future updates will add detailed role-based certification roadmaps and projects for each provider. Those additions are **Planned — Coming soon**.

| Role direction | Example work | A next practice task |
| --- | --- | --- |
| Cloud operations or administration | Keep services working and manage access | Explain a log entry and write a response to a service failure |
| Cloud application development | Build applications using cloud services | Run a small app locally and describe the service it would need online |
| Cloud architecture | Design systems and explain tradeoffs | Compare two possible designs for the same small app |
| Cloud data work | Store, transform, and analyze information | Clean a small public dataset locally and explain the result |

Role-based certifications focus on particular work. Future guides will verify current provider names and prerequisites rather than assuming a fundamentals certificate is always mandatory.
