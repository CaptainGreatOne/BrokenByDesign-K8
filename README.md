# Kubernetes Platform Engineering Lab

A progressive, failure-driven Kubernetes learning repository built on KIND.
Designed to teach not just how to use Kubernetes — but how to think in Kubernetes.

## Note
This Repository is meant to surve two purposes. 
1) To assist developers and engineers in learning Kubernetes, and how Kubernetes interacts in a production environment. 
2)  To be a continuation of the original Broken By Design lab. In the original Broken By Design, a developer can learn about observation of an application in the context of Docker. In this repository, a developer can learn about observation, but within the context of Kubernetes. I recommend heading to the first repository, which can be found here → [Broken By Design](https://github.com/CaptainGreatOne/BrokenbyDesign).

### 📌 Purpose
This repository is not a collection of YAML files.

It is a structured, layered lab designed to move from:

```
Basic Kubernetes usage
    → Operational confidence
    → Helm & release management
    → GitOps workflows
    → Secrets management
    → Full production-style observability
```

The goal is not just to deploy things.

The goal is to understand:
- Why Kubernetes behaves the way it does
- How failures happen
- How reconciliation works
- How to debug confidently
- How real production responsibilities differ between roles


### 🧠 Learning Philosophy
Most tutorials focus on:

“Here is the YAML. Now it works.”

This lab focuses on:
- Mental models
- System behavior
- Failure analysis
- Controlled experimentation
- Operational thinking
- Every section builds on the previous one.

Each phase introduces:
- A new abstraction
- A new operational responsibility
- Intentional failure scenarios
- Debugging exercises
- Production-style mindset

You are not just deploying applications.

You are learning how distributed systems behave under orchestration.

### 🏗️ Repository Structure
```k8s-platform-lab/
│
├── 00-foundations-kind/
├── 01-core-kubernetes/
├── 02-failure-labs/
├── 03-helm/
├── 04-gitops/
├── 05-secrets-management/
├── 06-observability/
│
├── app/
├── scripts/
└── README.md
```

### Project Directory
- [PHASE 00 - Foundations](00-foundations-kind/README.md)
- [PHASE 01 - Core Kubernetes](01-core-kubernetes/README.md)
- [PHASE 02 - Kubernetes Failures](02-failure-labs/README.md)
- [PHASE 03 - Helm](03-helm/README.md)
- [PHASE 04 - Gitops](04-gitops/README.md)
- [PHASE 05 - Secrets Management](05-secrets-management/README.md)
- [PHASE 6 - Observability](06-observability/README.md)

### 🔁 How to Use This Lab
Each phase contains:
- Step-by-step exercises
- Failure scenarios
- Debugging tasks
- Explanations
- Reflection questions

Progress sequentially.

Do not skip phases.

Depth matters more than speed.

### 🎯 End Goal
By the end of this repository, you should be able to:
- Deploy applications to Kubernetes confidently
- Debug failures systematically
- Use Helm properly
- Implement GitOps workflows
- Manage secrets securely
- Observe and monitor distributed systems
- Explain Kubernetes concepts clearly to others

### 📚 Why This Exists
This project exists because:
- Surface-level tutorials do not create operational confidence.
- Kubernetes knowledge often remains abstract.
- Understanding comes from controlled failure.
- Teaching requires depth.

