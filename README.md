# 🏗️ Cloud Landing Zones

A free, self-updating guide to **landing zones on every major cloud**: the secure, governed multi-account foundation you build before any workload, including AI. Official frameworks, reference code and research, side by side for each hyperscaler.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Last refreshed: 2026-10-11 10:54 UTC_
<!-- STAMP:END -->

## Contents
- [Latest research](#-latest-research)
- [Landing zones by hyperscaler](#-landing-zones-by-hyperscaler)
- [What every landing zone covers](#-what-every-landing-zone-covers)
- [Landing zone code (Terraform, Bicep, CDK)](#-landing-zone-code-terraform-bicep-cdk)
- [AI and GenAI landing zones](#-ai-and-genai-landing-zones)
- [Policy as code and cloud governance](#-policy-as-code-and-cloud-governance)
- [Free learning resources](#-free-learning-resources)
- [How this repo stays fresh](#-how-this-repo-stays-fresh)

## 📄 Latest research
Newest papers on arXiv for this topic, newest first.

<!-- ARXIV:START -->
| Date | Paper | Authors |
|---|---|---|
| 2026-07-22 | [Enterprise Integration Modernization with SAP BTP](https://arxiv.org/abs/2607.19662) | Shunmukha Sagar Puppala |
| 2026-07-02 | [LLMoxie: Exploring Agentic AI for Scientific Software Development](https://arxiv.org/abs/2607.02703) | Landung Setiawan et al. |
| 2026-06-09 | [Synthetic-to-Real Pipeline for Safe Landing Zone Detection](https://arxiv.org/abs/2606.14767) | Shrikant Banerjee et al. |
| 2026-01-16 | [Crane Lowering Guidance Using a Attachable Camera Module for Driver Vision Support](https://arxiv.org/abs/2601.11026) | HyoJae Kang et al. |
| 2026-01-11 | [How Do Ports Organise Innovation? Linking Port Governance, Ownership, and Living Labs](https://arxiv.org/abs/2601.06894) | Sonia Yeh et al. |
| 2026-01-07 | [Hybrid Cloud Architectures for Research Computing: Applications and Use Cases](https://arxiv.org/abs/2601.04349) | Xaver Stiensmeier et al. |
| 2025-12-11 | [A Privacy-Preserving Cloud Architecture for Distributed Machine Learning at Scale](https://arxiv.org/abs/2512.10341) | Vinoth Punniyamoorthy et al. |
| 2025-12-10 | [Development and Testing for Perception Based Autonomous Landing of a Long-Range QuadPlane](https://arxiv.org/abs/2512.09343) | Ashik E Rasul et al. |
<!-- ARXIV:END -->

## ☁️ Landing zones by hyperscaler

| Cloud | Framework (free docs) | Official reference code |
|---|---|---|
| **AWS** | [Landing zone guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-aws-environment/understanding-landing-zones.html) · [AWS Control Tower](https://docs.aws.amazon.com/controltower/) | [Landing Zone Accelerator](https://github.com/awslabs/landing-zone-accelerator-on-aws) · [Account Factory for Terraform](https://github.com/aws-ia/terraform-aws-control_tower_account_factory) |
| **Microsoft Azure** | [Azure landing zones (CAF)](https://learn.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/) | [Enterprise-Scale](https://github.com/Azure/Enterprise-Scale) · [ALZ-Bicep](https://github.com/Azure/ALZ-Bicep) |
| **Google Cloud** | [Landing zone design](https://docs.cloud.google.com/architecture/landing-zones) · [Enterprise foundations blueprint](https://cloud.google.com/architecture/security-foundations) | [terraform-example-foundation](https://github.com/terraform-google-modules/terraform-example-foundation) · [Cloud Foundation Fabric](https://github.com/GoogleCloudPlatform/cloud-foundation-fabric) |
| **IBM Cloud** | [Landing zone docs](https://cloud.ibm.com/docs/secure-infrastructure-vpc) | [terraform-ibm-landing-zone](https://github.com/terraform-ibm-modules/terraform-ibm-landing-zone) |
| **Oracle Cloud (OCI)** | [OCI Well-Architected Framework](https://docs.oracle.com/en/solutions/oci-best-practices/) | [OCI Core Landing Zone](https://github.com/oci-landing-zones/terraform-oci-core-landingzone) |
| **Huawei Cloud** | [Huawei Cloud documentation](https://support.huaweicloud.com/intl/en-us/) (search "landing zone" / Organizations) | See the auto-updated code lists below |

## 🧭 What every landing zone covers

Identity and access · account or subscription structure · networking and connectivity · security baselines and logging · policy and compliance guardrails · cost management · a repeatable way to create new accounts. Regulated industries such as banking add data residency, key management and evidence for the regulator.

## 🧱 Landing zone code (Terraform, Bicep, CDK)
Most-starred GitHub repositories updated in the last 12 months.

<!-- IAC:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [GoogleCloudPlatform/cloud-foundation-fabric](https://github.com/GoogleCloudPlatform/cloud-foundation-fabric) | End-to-end modular samples and landing zones toolkit for Terraform on GCP. | HCL | 2,113 | 2026-10-09 |
| [Azure/agent-landing-zone](https://github.com/Azure/agent-landing-zone) | Enterprise-grade landing zone for AI agent applications on Azure. Deploy the secure infrastructure, the agent app, or both — built on Micros | Python | 1,187 | 2026-10-10 |
| [Azure/ALZ-Bicep](https://github.com/Azure/ALZ-Bicep) | This repository contains the Azure Landing Zones (ALZ) Bicep (Classic) modules that help deliver and deploy the Azure Landing Zone conceptua | Bicep | 890 | 2026-10-09 |
| [Azure/AI-Landing-Zones](https://github.com/Azure/AI-Landing-Zones) | The AI Landing Zone is a secure, resilient and scalable reference architecture and reference implementation in the form of bicep, terraform  | Python | 344 | 2026-10-10 |
| [Azure/appservice-landing-zone-accelerator](https://github.com/Azure/appservice-landing-zone-accelerator) | The Azure App Service landing zone accelerator is an open-source collection of architectural guidance and reference implementation to accele | Bicep | 238 | 2026-03-24 |
| [Jamonygr/azure-landing-zone-lab](https://github.com/Jamonygr/azure-landing-zone-lab) | Learn Azure infrastructure with this hands-on Terraform lab. Deploys a complete enterprise environment with hub-spoke networking, firewall,  | HCL | 236 | 2026-08-24 |
<!-- IAC:END -->

## 🤖 AI and GenAI landing zones
Most-starred GitHub repositories updated in the last 12 months.

<!-- AILZ:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [Azure/agent-landing-zone](https://github.com/Azure/agent-landing-zone) | Enterprise-grade landing zone for AI agent applications on Azure. Deploy the secure infrastructure, the agent app, or both — built on Micros | Python | 1,187 | 2026-10-10 |
| [Azure/AI-Landing-Zones](https://github.com/Azure/AI-Landing-Zones) | The AI Landing Zone is a secure, resilient and scalable reference architecture and reference implementation in the form of bicep, terraform  | Python | 344 | 2026-10-10 |
| [Azure/terraform-azurerm-avm-ptn-aiml-landing-zone](https://github.com/Azure/terraform-azurerm-avm-ptn-aiml-landing-zone) | Terraform Azure Verified Pattern Module for AI-ML - Landing Zone (LZ) | HCL | 41 | 2026-10-08 |
| [DataChefHQ/aws-data-landing-zone](https://github.com/DataChefHQ/aws-data-landing-zone) | The Data Landing Zone is a CDK Construct designed to create a landing zone tailored for supporting and enabling AI, data-driven, data mesh,  | TypeScript | 25 | 2026-10-11 |
| [Azure/bicep-ptn-aiml-landing-zone](https://github.com/Azure/bicep-ptn-aiml-landing-zone) | AI Landing Zone Bicep templates for deploying a secure, modular baseline for AI applications and agents on Azure. | PowerShell | 19 | 2026-09-29 |
| [Azure/SAIL](https://github.com/Azure/SAIL) | The Sovereign AI Landing Zone deployment template is an open-source Infrastructure as Code (IaC) solution designed to deploy LLM models to r | Bicep | 12 | 2026-05-25 |
<!-- AILZ:END -->

## 🛡️ Policy as code and cloud governance
Most-starred GitHub repositories updated in the last 12 months.

<!-- GOV:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [cloud-custodian/cloud-custodian](https://github.com/cloud-custodian/cloud-custodian) | Rules engine for cloud security, cost optimization, and governance, DSL in yaml for policies to query, filter, and take actions on resources | Python | 6,082 | 2026-10-09 |
| [iann0036/iamlive](https://github.com/iann0036/iamlive) | Generate an IAM policy from AWS, Azure, or Google Cloud (GCP) calls using client-side monitoring (CSM) or embedded proxy | Go | 3,413 | 2026-04-19 |
| [Micke-K/IntuneManagement](https://github.com/Micke-K/IntuneManagement) | Copy, export, import, delete, document and compare policies and profiles in Intune and Azure with PowerShell script and WPF UI. Import ADMX  | PowerShell | 2,099 | 2026-09-23 |
| [Azure/azure-policy](https://github.com/Azure/azure-policy) | Repository for Azure Resource Policy built-in definitions and samples | Open Policy Agent | 1,695 | 2026-09-20 |
| [aws-cloudformation/cloudformation-guard](https://github.com/aws-cloudformation/cloudformation-guard) | Guard offers a policy-as-code domain-specific language (DSL) to write rules and validate JSON- and YAML-formatted data such as CloudFormatio | Rust | 1,390 | 2026-09-14 |
| [JulianHayward/Azure-MG-Sub-Governance-Reporting](https://github.com/JulianHayward/Azure-MG-Sub-Governance-Reporting) | Azure Governance Visualizer aka AzGovViz is a PowerShell script that captures Azure Governance related information such as Azure Policy, RBA | PowerShell | 981 | 2026-09-11 |
<!-- GOV:END -->

## 📚 Free learning resources

| Resource | Why it's useful |
|---|---|
| [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/) | Design principles, incl. security and ML lenses |
| [Microsoft Cloud Adoption Framework](https://learn.microsoft.com/azure/cloud-adoption-framework/) | Strategy, governance and landing zones |
| [Google Cloud Architecture Framework](https://cloud.google.com/architecture/framework) | Google's design pillars |
| [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) | Free security baselines for each cloud |
| [Terraform tutorials](https://developer.hashicorp.com/terraform/tutorials) | Free infrastructure-as-code training |

## 🔄 How this repo stays fresh
A GitHub Action runs every day. It queries the public arXiv API for new papers and the GitHub search API for active, popular repositories, then rewrites the lists above. The code is in [`scripts/hub_refresh.py`](scripts/hub_refresh.py) and the search terms are in [`hub.json`](hub.json).

Inclusion in a list is automatic and is not an endorsement. Check each project's license before reuse.

---
Curated by [Mohammad Alrashed](https://github.com/DatariusAI). Part of a series of free AI hubs: see the [profile page](https://github.com/DatariusAI) for industry, cloud and mathematics hubs. Contributions welcome by pull request.
