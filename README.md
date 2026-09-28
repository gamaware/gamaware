# Alex Garcia

![Alex Garcia, AWS DevOps Engineer and Cloud Architect](assets/banner.png)

AWS DevOps Engineer and Cloud Architect based in Mexico, working US Central hours.

I'm an AWS DevOps engineer with more than 17 years in IT. I build and repair AWS infrastructure and delivery
pipelines using Terraform, AWS CDK, CI/CD and containers. I document the plan before making any change, submit pull
requests for your team's review, and remove the access you gave me when I hand over the work.

[![Hire me on Upwork](https://img.shields.io/badge/Hire%20me%20on-Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~014b3520cf9e140103)
[![Portfolio](https://img.shields.io/badge/Portfolio-AWS%20%26%20DevOps-243B53?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gamaware/aws-devops-portfolio)

## What I do

Each service links to a public repository with a sample deliverable or working code you can inspect.

- **Terraform on AWS audit and fix**: a ranked diagnosis of risky infrastructure code, fixes as pull requests and a
  state migration that destroys nothing. Evidence:
  [`terraform-aws-rescue-lab`](https://github.com/gamaware/terraform-aws-rescue-lab)
- **CI/CD pipeline to AWS**: keyless deploys through OIDC, with image scanning and automatic rollback. Evidence:
  [`github-actions-aws-oidc-lab`](https://github.com/gamaware/github-actions-aws-oidc-lab)
- **AWS security and IAM review**: findings ranked by risk, policy rewrites that narrow access, and a baseline set of
  guardrails. Evidence: [`aws-iam-security-review-sample`](https://github.com/gamaware/aws-iam-security-review-sample)
- **Kubernetes on Amazon EKS**: clusters built with Terraform and delivered through Helm and Argo CD. Evidence:
  [`terraform-aws-eks-gitops-lab`](https://github.com/gamaware/terraform-aws-eks-gitops-lab)
- **Containerize and deploy to ECS Fargate**: a repeatable, reversible path from one machine to AWS. Evidence:
  [`aws-ecs-fargate-deploy-lab`](https://github.com/gamaware/aws-ecs-fargate-deploy-lab)
- **AWS landing zone for a new project**: separate accounts, central sign-in, an audit trail and tested service
  control policies. Evidence:
  [`terraform-aws-landing-zone-lab`](https://github.com/gamaware/terraform-aws-landing-zone-lab)
- **DevOps and Well-Architected assessment**: a risk-rated backlog and a roadmap your team can execute. Evidence:
  [`aws-well-architected-assessment-sample`](https://github.com/gamaware/aws-well-architected-assessment-sample)
- **AWS cost optimization audit**: ranked savings with stated assumptions, plus tagging and ownership for the spend.
  Evidence: [`aws-cost-optimization-audit-sample`](https://github.com/gamaware/aws-cost-optimization-audit-sample)
- **Migration to AWS**: a wave plan and a cutover runbook with rollback triggers. Evidence:
  [`aws-migration-runbook-sample`](https://github.com/gamaware/aws-migration-runbook-sample)
- **AWS workshop and mentoring**: hands-on labs with starter code, solutions and tests. Evidence:
  [`aws-devops-workshop-labs`](https://github.com/gamaware/aws-devops-workshop-labs)

## Featured work

Every repository uses a fictional client and verifies its evidence offline, without an AWS account.

| Repository | Outcome |
| --- | --- |
| [`aws-devops-portfolio`](https://github.com/gamaware/aws-devops-portfolio) | Index of every service, with a check that keeps the whole collection consistent |
| [`terraform-aws-rescue-lab`](https://github.com/gamaware/terraform-aws-rescue-lab) | Untrusted Terraform turned into tested modules with remote state and a plan gate |
| [`github-actions-aws-oidc-lab`](https://github.com/gamaware/github-actions-aws-oidc-lab) | Long-lived CI keys replaced by OIDC, and deploys that fail when ECS rolls back |
| [`aws-iam-security-review-sample`](https://github.com/gamaware/aws-iam-security-review-sample) | Security review report with ranked findings and a control-to-evidence map for SOC 2 |
| [`terraform-aws-eks-gitops-lab`](https://github.com/gamaware/terraform-aws-eks-gitops-lab) | EKS through Terraform modules, a Helm chart and Argo CD folders per environment |
| [`aws-ecs-fargate-deploy-lab`](https://github.com/gamaware/aws-ecs-fargate-deploy-lab) | API containerized and deployed to Fargate with a circuit breaker and alarm-based rollback |
| [`terraform-aws-landing-zone-lab`](https://github.com/gamaware/terraform-aws-landing-zone-lab) | Multi-account foundation with AWS Organizations and guardrails tested against real requests |
| [`aws-well-architected-assessment-sample`](https://github.com/gamaware/aws-well-architected-assessment-sample) | Assessment across the pillars and the DevOps lens, with a ranked backlog and roadmap |
| [`aws-cost-optimization-audit-sample`](https://github.com/gamaware/aws-cost-optimization-audit-sample) | Savings split into quick wins and planned work, each recalculated from billing data |
| [`aws-migration-runbook-sample`](https://github.com/gamaware/aws-migration-runbook-sample) | Wave plan, AWS DMS tasks and a timed cutover runbook with a way back |
| [`aws-devops-workshop-labs`](https://github.com/gamaware/aws-devops-workshop-labs) | Numbered labs on AWS, Terraform, CDK and CI/CD, each tested against its solution |
| [`cdk-python-nag-pipeline-lab`](https://github.com/gamaware/cdk-python-nag-pipeline-lab) | CDK Pipelines app in Python that stops on any unacknowledged cdk-nag finding |

## AI on AWS

Clients now want AI in their platforms, not only faster pipelines. What I bring:

- **Generative AI platforms on AWS**: an internal LLM gateway and GenAI catalog on Amazon Bedrock, with ECS Fargate,
  API Gateway, Cognito and cross-region inference, designed for a retail chain.
- **AI inside delivery pipelines**: a CI security scanner that turns scanner output into a written assessment with
  Amazon Bedrock.
- **Agentic tooling for engineering teams**: coding assistants such as Claude Code, OpenAI Codex, Amazon Q Developer
  and Kiro, set up with MCP servers, shared skills and review workflows, plus hands-on workshops so teams adopt them.
- **Teaching**: an agentic AI unit (fundamentals and MCP) in the systems design course I teach.

[![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-01A88D?style=for-the-badge&logo=amazonwebservices&logoColor=white)](https://aws.amazon.com/bedrock/)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white)](https://www.anthropic.com/claude-code)
[![OpenAI](https://img.shields.io/badge/OpenAI%20Codex-412991?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2aWV3Qm94PSIwIDAgMjQwNiAyNDA2Ij4KCQoJPHBhdGggaWQ9ImEiIGQ9Ik0xMTA3LjMgMjk5LjFjLTE5Ny45OTkgMC0zNzMuOSAxMjcuMy00MzUuMiAzMTUuM0w2NTAgNzQzLjV2NDI3LjljMCAyMS40IDExIDQwLjQgMjkuNCA1MS40bDM0NC41IDE5OC41MTVWODMzLjNoLjF2LTI3LjlMMTM3Mi43IDYwNGMzMy43MTUtMTkuNTIgNzAuNDQtMzIuODU3IDEwOC40Ny0zOS44MjhMMTQ0Ny42IDQ1MC4zQzEzNjEgMzUzLjUgMTIzNy4xIDI5OC41IDExMDcuMyAyOTkuMXptMCAxMTcuNS0uNi42Yzc5LjY5OSAwIDE1Ni4zIDI3LjUgMjE3LjYgNzguNC0yLjUgMS4yLTcuNCA0LjMtMTEgNi4xTDk1Mi44IDcwOS4zYy0xOC40IDEwLjQtMjkuNCAzMC0yOS40IDUxLjRWMTI0OGwtMTU1LjEtODkuNFY3NTUuOGMtLjEtMTg3LjA5OSAxNTEuNjAxLTMzOC45IDMzOS0zMzkuMnoiIGZpbGw9IiNmZmYiLz4KCTx1c2UgeGxpbms6aHJlZj0iI2EiIHRyYW5zZm9ybT0icm90YXRlKDYwIDEyMDMgMTIwMykiLz4KICAJPHVzZSB4bGluazpocmVmPSIjYSIgdHJhbnNmb3JtPSJyb3RhdGUoMTIwIDEyMDMgMTIwMykiLz4KCTx1c2UgeGxpbms6aHJlZj0iI2EiIHRyYW5zZm9ybT0icm90YXRlKDE4MCAxMjAzIDEyMDMpIi8+Cgk8dXNlIHhsaW5rOmhyZWY9IiNhIiB0cmFuc2Zvcm09InJvdGF0ZSgyNDAgMTIwMyAxMjAzKSIvPgoJPHVzZSB4bGluazpocmVmPSIjYSIgdHJhbnNmb3JtPSJyb3RhdGUoMzAwIDEyMDMgMTIwMykiLz4KCjwvc3ZnPg==)](https://openai.com/codex/)
[![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-1F2937?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)](https://modelcontextprotocol.io/)

## Tech stack

[![Tech stack](https://skillicons.dev/icons?i=aws,terraform,kubernetes,docker,githubactions,gitlab,python,bash,linux,git)](https://skillicons.dev)

AWS, Terraform, AWS CDK, CloudFormation, Amazon EKS, Amazon ECS, Helm, Argo CD, GitHub Actions, GitLab CI,
AWS CodePipeline, Docker, Python, Bash, Checkov, Trivy, Amazon Bedrock, Claude Code, OpenAI Codex, MCP.

## Certifications

<p>
  <img src="assets/badges/cloudpractitioner.png" alt="AWS Certified Cloud Practitioner" title="AWS Certified Cloud Practitioner" width="96">
  <img src="assets/badges/aip.png" alt="AWS Certified AI Practitioner" title="AWS Certified AI Practitioner" width="96">
  <img src="assets/badges/saa.png" alt="AWS Certified Solutions Architect – Associate" title="AWS Certified Solutions Architect – Associate" width="96">
  <img src="assets/badges/developer.png" alt="AWS Certified Developer – Associate" title="AWS Certified Developer – Associate" width="96">
  <img src="assets/badges/sysops.png" alt="AWS Certified SysOps Administrator – Associate" title="AWS Certified SysOps Administrator – Associate" width="96">
  <img src="assets/badges/educator.png" alt="AWS Academy Certified Educator" title="AWS Academy Certified Educator" width="96">
  <img src="assets/badges/terraform.png" alt="HashiCorp Certified Terraform Associate" title="HashiCorp Certified Terraform Associate" width="96">
</p>

## Teaching

<a href="https://iteso.mx/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/iteso-dark.svg">
    <img src="assets/iteso.svg" alt="ITESO, Universidad Jesuita de Guadalajara" width="280">
  </picture>
</a>

Adjunct professor of Cloud Architecture and Scalable Systems Design at ITESO, the Jesuit University of Guadalajara.

## Contact

I work in English and Spanish, and I reply within a business day on weekdays.

[![Hire me on Upwork](https://img.shields.io/badge/Hire%20me%20on-Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~014b3520cf9e140103)
