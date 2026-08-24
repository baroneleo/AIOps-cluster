# AIOps Cluster

Laboratório Kubernetes local para construção de uma plataforma de AIOps/SRE autônoma.

Este repositório contém a configuração e os manifests utilizados para provisionar e validar um cluster Kubernetes local utilizando **Kind**, executando sobre **Docker Desktop/WSL2**.

O objetivo desta primeira etapa é criar uma infraestrutura Kubernetes reproduzível e funcional que servirá como base para as próximas etapas do laboratório, incluindo observabilidade, SRE, Chaos Engineering, detecção de problemas, Policy Engine, LLM e auto-remediação.

---

# 1. Pré-requisitos

Para reproduzir este laboratório, é necessário possuir:

- Windows
- Docker Desktop
- WSL2
- kubectl
- Kind
- Git

Validar as instalações:

```bash
docker version

kubectl version --client

kind version

git --version

