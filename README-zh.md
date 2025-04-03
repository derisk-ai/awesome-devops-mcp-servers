# Awesome DevOps MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![简体中文](https://img.shields.io/badge/中文文档-点击查看-orange)](README-zh.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)

A curated list of awesome Model Context Protocol (MCP) servers for DevOps.

* [What is MCP?](#what-is-mcp)
* [Infrastructure as Code](#infrastructure-as-code)
* [Container Orchestration](#container-orchestration)
* [CI/CD](#cicd)
* [Monitoring & Observability](#monitoring--observability)
* [Security](#security)
* [Utilities](#utilities)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers for DevOps workflows.

## Legend

* 🎖️ – official implementation
* programming language
  * 🐍 – Python codebase
  * 📇 – TypeScript codebase
  * 🏎️ – Go codebase
  * 🦀 – Rust codebase
* scope
  * ☁️ - Cloud Service
  * 🏠 - Local Service

## Infrastructure as Code

MCP servers for infrastructure provisioning and management.

- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) 🦀 🏠 - Terraform MCP server for managing infrastructure as code
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) 🐍 ☁️ - Execute AWS CLI commands in a secure Docker environment
- [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp) 🐍 ☁️ - Azure CLI wrapper for direct Azure management
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) 🐍 ☁️ - VMware ESXi/vCenter management server

## Container Orchestration

Kubernetes and container management MCP servers.

- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) 🐍 - Kubernetes CLI commands execution
- [flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) 📇 ☁️/🏠 - Kubernetes cluster operations
- [manusa/Kubernetes MCP Server](https://github.com/manusa/kubernetes-mcp-server) 🏎️ 🏠 - Powerful Kubernetes server with OpenShift support
- [weibaohui/k8m](https://github.com/weibaohui/k8m) 🏎️ ☁️/🏠 - Multi-cluster Kubernetes management with 50+ tools

## CI/CD

Continuous integration and delivery MCP servers.

- [jenkins-mcp-server](https://github.com/jenkinsci/mcp-plugin) 🏎️ 🏠 - Jenkins automation server integration
- [argocd-mcp-server](https://github.com/argoproj-labs/argocd-mcp) 🏎️ ☁️ - ArgoCD GitOps continuous delivery
- [github-actions-mcp](https://github.com/actions/mcp-server) 📇 ☁️ - GitHub Actions workflow management

## Monitoring & Observability

Observability and monitoring MCP servers.

- [prometheus-mcp-server](https://github.com/prometheus-community/mcp-server) 🏎️ 🏠 - Prometheus monitoring system
- [grafana-mcp-server](https://github.com/grafana/mcp-plugin) 📇 ☁️ - Grafana metrics visualization
- [datadog-mcp-server](https://github.com/DataDog/mcp-integration) 🐍 ☁️ - Datadog monitoring integration

## Security

DevOps security MCP servers.

- [vault-mcp-server](https://github.com/hashicorp/vault-mcp) 🏎️ 🏠 - HashiCorp Vault secrets management
- [aqua-mcp-server](https://github.com/aquasecurity/mcp-plugin) 🏎️ ☁️ - Aqua Security container scanning
- [snyk-mcp-server](https://github.com/snyk/mcp-integration) 📇 ☁️ - Snyk vulnerability scanning

## Utilities

Other useful DevOps MCP servers.

- [ansible-mcp-server](https://github.com/ansible-community/mcp-plugin) 🐍 🏠 - Ansible configuration management
- [pulumi-mcp-server](https://github.com/pulumi/mcp-integration) 🏎️ ☁️ - Pulumi infrastructure as code
- [terragrunt-mcp-server](https://github.com/gruntwork-io/mcp-plugin) 🏎️ 🏠 - Terragrunt wrapper for Terraform