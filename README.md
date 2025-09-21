# Developer Platform

This repository serves as a comprehensive developer platform for cloud infrastructure experiments across Google Cloud Platform (GCP) and Amazon Web Services (AWS).

## Purpose

Primary platform for conducting infrastructure experiments, testing cloud-native solutions, and developing application and operational workflows across multiple cloud providers.

## Technology Stack

- **Infrastructure as Code**: OpenTofu (Terraform fork) for provisioning and managing cloud resources
- **GitOps Controller**: OpenTofu Controller for managing infrastructure deployments through Git
- **Continuous Delivery**: Argo CD for GitOps workflows and application deployment
- **Container Orchestration**: Kubernetes for containerized application management

## Repository Structure

- `platform/` - Platform components like the opentofu contoller & eso.
- `modules/` - Modules for infrastructure provisioning and management
- `catalog` - Resource definitions for infrastructure provisioning and management
- `scripts/` - Utility scripts, automation tools, and deployment helpers
- `justfile` - Just command runner for common development and deployment tasks
- `kind.yaml` - Kubernetes in Docker configuration for local development

## Getting Started

This platform is designed to support rapid experimentation with cloud infrastructure patterns, GitOps workflows, and multi-cloud architectures.
