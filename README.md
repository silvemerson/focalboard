# Focalboard - Manifesto Kubernetes

Este é o manifesto Kubernetes para o [Focalboard](https://www.focalboard.com/).

Focalboard é uma alternativa open source e auto-hospedada ao Trello, Notion e Asana.

Ele ajuda a definir, organizar, acompanhar e gerenciar o trabalho entre indivíduos e equipes.

O código-fonte do Focalboard está disponível [neste repositório](https://github.com/mattermost-community/focalboard).

O fork trás muita coisa no projeto oficial de helm chart, então resolvi isolar aqui. 

---
⚠️ AVISO

Este repositório https://github.com/mattermost-community/focalboard atualmente não está sendo mantido. Se você tem interesse em se tornar um mantenedor, entre em contato no repo oficial.

---

## 1. Pré-requisitos

### 1.1 Cluster Kubernetes

Você precisa de um cluster Kubernetes (v1.16+).

Caso ainda não tenha um, veja as opções de instalação aqui:  
👉 https://kubernetes.io/docs/setup/pick-right-solution/

### 1.2 kubectl

Instale e configure o `kubectl` conforme sua distribuição:  
👉 https://kubernetes.io/docs/tasks/tools/

---

## 2. Rodando localmente com `kubectl apply`

Clone este repositório (ou use um fork seu):

```bash
git clone https://github.com/silvemerson/focalboard.git

cd focalboard

kubectl apply -f manifest
```