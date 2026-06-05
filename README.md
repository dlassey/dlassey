<div align="center">

# Dosseh Lassey

### Technology Consultant — Infrastructure Platforms · Automation · AI Systems

Infrastructure • Platform Engineering • Automation • AI • Governance
Bilingual FR/EN

[Website](https://dossehlassey.me) · [LinkedIn](https://linkedin.com/in/your-handle) · contact@dossehlassey.me

</div>

---

## About

I design, automate and operate production-grade infrastructure, then document every
decision. I work where infrastructure,
automation, AI and governance meet, and I keep one foot in delivery (DL Axis consulting)
and one in hands-on engineering (DL Labs).


---

## Stack

**Virtualization & Infrastructure as Code**

<p align="left">
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/proxmox.svg" title="Proxmox VE" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/vmware.svg" title="VMware vSphere" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/terraform.svg" title="Terraform" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/ansible.svg" title="Ansible" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/gitlab.svg" title="GitLab CI/CD" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/awx.svg" title="AWX" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/argo-cd.svg" title="ArgoCD" />
</p>

**Network, Platform & Storage**

<p align="left">
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/opnsense.svg" title="OPNsense" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/pi-hole.svg" title="Pi-hole DNS" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/tailscale.svg" title="Tailscale" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/docker.svg" title="Docker / Compose" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/k3s.svg" title="k3s" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/truenas.svg" title="TrueNAS / ZFS" />
</p>

**Security, Identity & Observability**

<p align="left">
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/hashicorp-vault.svg" title="HashiCorp Vault (KV + internal CA)" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/keycloak.svg" title="Keycloak" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/wazuh.svg" title="Wazuh SIEM/HIDS" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/zabbix.svg" title="Zabbix" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/grafana.svg" title="Grafana" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/netbox.svg" title="NetBox IPAM" />
</p>

**Local AI & Automation**

<p align="left">
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/ollama.svg" title="Ollama — local LLMs" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/n8n.svg" title="n8n" />&nbsp;&nbsp;
  <img height="40" src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/svg/mkdocs.svg" title="MkDocs" />
</p>

> Ollama runs qwen3, deepseek-r1 and coder models; orchestration via Dify, observability
> via Langfuse, and a custom **MCP server** (Node/Express) exposes the lab's infrastructure
> as agent-callable tools.

---

## Featured work

**Platform & IaC** — Terraform (`bpg/proxmox`) provisioning driven through GitLab CI/CD
(`validate → plan → apply`), secrets pulled from Vault, post-provisioning with Ansible/AWX.

**Security engineering** — HashiCorp Vault with a two-tier internal PKI (offline root CA +
online intermediate), Wazuh detection, and a zero-trust design (PKI + Keycloak + reverse
proxy + VLAN micro-segmentation).

**VMware → Proxmox migration** — native importer workflow (VMDK → qcow2), POC validated,
being industrialised into a client-facing runbook for DL Axis.

**AI on local models** — RAG pipelines and an MCP bridge that lets agents query and act on
the lab, built with governance (AIGP, Loi 25) as a first-class constraint.

---

## Why governance, not just tooling

Background in IT governance — ITIL, PMP, COBIT, MBA; **AIGP** and **AB-731** in progress.
Every project in the lab ships with bilingual (FR/EN) documentation and an architecture
decision record, because in the environments I target the runbook matters as much as the
deploy. This is the angle I bring that pure tooling profiles don't: systems that are
auditable, reproducible and explainable — not just running.

---

## Currently exploring

Honest experiments, not yet production in the lab: agentic orchestration (LangGraph),
self-service infrastructure portals, certificate automation (ACME / cert-manager), and
remote-state collaboration (MinIO backend for Terraform).

---

## Goals

- Reproducible, documented infrastructure platforms — IaC end to end.
- Deeper AI-governance practice tied to real deployments (AIGP, Loi 25).
- A repeatable VMware-to-Proxmox migration offering for SMEs.
- Public, hands-on learning artifacts through DL Labs.

---

## Connect

Docs & write-ups → **labs.dossehlassey.me**
Website → **dossehlassey.me** · LinkedIn → *[your-handle]* · contact@dossehlassey.me

<div align="center">

**Build → Automate → Measure → Improve**

</div>
