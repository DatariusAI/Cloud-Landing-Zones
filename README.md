# 🏗️ Cloud Landing Zones

A free, self-updating guide to **landing zones on every major cloud**: the secure, governed multi-account foundation you build before any workload, including AI. Official frameworks, reference code and research, side by side for each hyperscaler.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Lists fill in after the first daily refresh._
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
_Loading on first refresh._
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
_Loading on first refresh._
<!-- IAC:END -->

## 🤖 AI and GenAI landing zones
Most-starred GitHub repositories updated in the last 12 months.

<!-- AILZ:START -->
_Loading on first refresh._
<!-- AILZ:END -->

## 🛡️ Policy as code and cloud governance
Most-starred GitHub repositories updated in the last 12 months.

<!-- GOV:START -->
_Loading on first refresh._
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
