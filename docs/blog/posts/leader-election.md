---
tags:
  - Kubernetes
---
# What is Leader Election in Kubernetes

Have you ever wondered what would happen if the same controller were installed multiple times in a cluster? Which instance would take ownership of the resources and reconcile them, and would this lead to conflicts between controller instances that could potentially corrupt or destabilize your resources?
