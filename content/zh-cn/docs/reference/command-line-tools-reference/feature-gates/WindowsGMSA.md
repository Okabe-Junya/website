---
# Removed from Kubernetes
title: WindowsGMSA
content_type: feature_gate

_build:
  list: never
  render: false

stages:
  - stage: alpha 
    defaultValue: false
    fromVersion: "1.14"
    toVersion: "1.15"
  - stage: beta 
    defaultValue: true
    fromVersion: "1.16"
    toVersion: "1.17"
  - stage: stable
    defaultValue: true
    fromVersion: "1.18"
    toVersion: "1.18"

removed: true
---

<!--
Enables passing of GMSA credential specs from pods to container runtimes.
-->
允许从 Pod 传递 GMSA 凭据规范到容器运行时。
