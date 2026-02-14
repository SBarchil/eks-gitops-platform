# Cloud-Native GitOps Platform (EKS)

A production-style Kubernetes platform built on Amazon EKS to demonstrate modern Platform Engineering and SRE practices.

This project implements a **GitOps-first workflow** using Argo CD, progressive delivery with Argo Rollouts, Istio-based traffic management, strict mTLS enforcement, governance policies via Kyverno, and observability-driven rollback using Prometheus.

---

## 🎯 Platform Objectives

This repository simulates a small internal developer platform designed to:

- Enable safe, Git-driven application deployments  
- Reduce production risk through canary releases and automated rollback  
- Enforce zero-trust service-to-service communication  
- Apply governance guardrails to prevent unsafe configurations  
- Provide observability signals to support reliability decisions  

---

## 🏗 Architecture Layers

The platform is structured into clear, production-oriented layers:

- **Delivery Layer** → Argo CD + Argo Rollouts  
- **Traffic Layer** → Istio (Ingress + Canary Routing)  
- **Security Layer** → STRICT mTLS + AuthorizationPolicies  
- **Governance Layer** → Kyverno  
- **Observability Layer** → Prometheus  

---

## 📌 Design Philosophy

The goal of this project is not to demonstrate isolated tools, but to model how a real platform team:

- Controls change safely  
- Minimizes deployment blast radius  
- Automates reliability guardrails  
- Separates application concerns from platform concerns  

This repository represents a structured, layered approach to cloud-native platform design.

