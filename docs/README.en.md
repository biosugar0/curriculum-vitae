# Resume

English | [日本語](README.md)

## Basic Information

| Item          | Details                                                            |
| ------------- | ------------------------------------------------------------------ |
| Name          | Yuto Kimura                                                        |
| Date of Birth | September 1994                                                     |
| Residence     | Tokyo, Japan                                                       |
| Education     | Tokyo Denki University, Graduate School of Science and Engineering |

| Platform | Link                                        |
| -------- | ------------------------------------------- |
| Blog     | [biosugar0.com](http://biosugar0.com)       |
| Zenn     | [biosugar0.com](https://zenn.dev/biosugar0) |
| Twitter  | [@biosugar0](https://twitter.com/biosugar0) |
| Email    | biosugar0@gmail.com                         |

## Education and Work Experience

| Date     | Details                                                                                                        |
| -------- | -------------------------------------------------------------------------------------------------------------- |
| Mar 2019 | Completed Master’s Program in Life Science, Tokyo Denki University, Graduate School of Science and Engineering |
| Apr 2019 | Joined a startup company in Tokyo as a Backend Engineer                                                        |
| Jun 2019 | Left the startup company                                                                                       |
| Jul 2019 | Joined Smart Shopping Inc. as a Backend Engineer                                                               |
| Nov 2021 | Transferred to the SRE department at Smart Shopping Inc.                                                       |

### Degree

- Master of Engineering, Major in Molecular Biology

## Areas of Expertise

### Engineering

- Backend API Development
- Microservices Development
- Domain-Driven Design
- Infrastructure as Code (Terraform)
- Cloud Infrastructure (AWS)
- Kubernetes (EKS) Deployment and Management
- Site Reliability Engineering (SRE)
- Application Development Using LLM

### Other

- SRE Team Formation
- Promoting DevOps in Development Organizations and Improving Developer Experience

## Skills

### Programming Languages

| Language   | Experience |
| ---------- | ---------- |
| Go         | 5 years    |
| Bash       | 6 years    |
| Python     | 2 years    |
| TypeScript | 1 year     |

### Other Experience

| Name           | Experience |
| -------------- | ---------- |
| Kubernetes     | 4 years    |
| Docker         | 4 years    |
| Terraform      | 3 years    |
| GitHub Actions | 2 years    |
| Datadog        | 3 years    |
| Vim            | 7 years    |

## Work Experience

### Startup Company in Tokyo (Aug 2018 - Oct 2018, Apr 2019 - Jun 2019)

#### Backend Engineer

- Developed backend for an automated platform for public cloud environment setup and operations
  - Developed features to support GCP infrastructure setup
  - Developed RBAC services used by microservices
  - Developed a browser-based SSH session manager

### Smart Shopping Inc. (Jul 2019 - Present)

#### Backend Engineer (Jul 2019 - Nov 2021)

- Full replacement of in-house inventory management SaaS
  - Migration from EC2 to EKS
  - Development of microservices
  - Containerization
  - Establishment of GitOps with GitHub Actions
  - Terraform implementation
- Expansion of ordering functions, addition of ordering methods for medical institutions, development of bulk parameter change functionality
- Built a service health score foundation
- Automated testing for Go applications

#### SRE (Nov 2021 - Present)

- Re-established the SRE team
  - Defined the role and mission of SRE
  - Established methods for collaboration with product development teams
  - Created an SRE roadmap
  - Measured and visualized toil
- Improved CI/CD, reduced toil, standardized detailed design documents
- Enabled self-service infrastructure changes
- Optimized AWS costs: fixed memory leaks, adjusted resources with Datadog, migrated EBS to gp3
- Led productivity improvements, received the Findy Team+ Award 2023
  - Developed GitHub Actions to split pull requests
  - Simplified and automated deployment flow with GitHub Flow
  - Facilitated regular meetings for identifying and resolving issues
- Enhanced observability: introduced structured logging, developed a common logging package
- Introduced GitHub Copilot for Business, set up OpenAI organizational accounts
- Managed k8s middleware with GitOps, developed an internal LLM Slack Bot
- Implemented Node Local DNS Cache, optimized server resources
- Codified new microservice deployment settings
- Managed Datadog monitoring settings with Terraform
- Simplified EKS updates
- Developed an AI meeting minutes system integrated with Google Drive

## Project Examples

### 1. Enhancing EKS Usability and Security

- **Project Overview:** Improved the usability and security of the EKS infrastructure, enhancing developer convenience and reducing overall system security risks.
- **Role:** Responsible for planning, implementation, and operation.
- **Achievements:** Improved permission management with EKS Pod Identity, enhanced security and efficiency of secret management with external secret operator.

### 2. Developing an AI Meeting Minutes System

- **Project Overview:** Developed a system that automatically generates meeting minutes from video and audio files uploaded to Google Drive and allows searching and sharing via a Slack Bot.
- **Role:** Responsible for planning, implementation, and operation.
- **Achievements:** Reduced employee workload and improved productivity. Integrated the generated meeting minutes search function into the LLM Slack Bot.

### 3. Reducing Infrastructure Costs

- **Project Overview:** Controlled and reduced increasing infrastructure costs.
- **Role:** Solely responsible for planning and execution.
- **Achievements:** Reduced AWS costs by 15% monthly through fixing memory leaks, optimizing resource settings, and migrating EBS to gp3.

### 4. Simplifying EKS Updates

- **Project Overview:** Streamlined the EKS update process, reducing workload.
- **Role:** Responsible for planning, implementation, testing, and deployment.
- **Achievements:** Transitioned from bi-annual large-scale updates to incremental updates.

### 5. Introducing Structured Logging

- **Project Overview:** Changed application logs to JSON format in Go applications and integrated context information.
- **Role:** Responsible for planning, design, and development.
- **Achievements:** Enabled automatic log parsing and improved visibility with Datadog, facilitating detailed investigation.

### 6. Developing an Internal Slack Bot with OpenAI API

- **Project Overview:** Aimed to improve internal productivity by developing a Slack Bot integrating ChatGPT API.
- **Role:** Responsible for planning, infrastructure setup, application implementation, and deployment.
- **Achievements:** Provided an environment where all employees can easily use LLM, utilized in various scenarios.

### 7. Improving Development Productivity

- **Project Overview:** Promoted DevOps to improve developer productivity and enhance four keys metrics, awarded the Findy Team+ Award 2023.
- **Role:** Project leader responsible for regular facilitation, rule formulation, and implementation of cycle time reduction mechanisms.
- **Achievements:** Reduced the cycle time from commit to deployment from an average of 10 days to 1 day.

### 8. Enabling Self-Service Infrastructure Changes

- **Project Overview:** Implemented self-service infrastructure management using Terraform and GitHub Actions to enable development teams to independently make infrastructure changes.
- **Role:** Responsible for planning, implementation, and operation.
- **Achievements:** Automated infrastructure change processes via pull requests, improving development speed and reducing SRE team workload.

### 9. Re-Establishing the SRE Team

- **Project Overview:** Dedicated the SRE team to practicing Site Reliability Engineering to improve product reliability.
- **Role:** Led the re-establishment of the SRE team.
- **Achievements:** Re-defined clear mission, vision, and values, transforming the team into a proactive and autonomous unit.

## Personal PR

I enjoy creating new things as an engineer, but I believe the essence lies in operations. I believe that by focusing on SRE and platform engineering, we can achieve a balance of development speed and stability, accelerating business not only in large enterprises but also in small and medium-sized organizations.

I am particularly drawn to businesses that provide services that make people's lives more convenient or improve inefficient tasks. By accelerating such businesses as a software engineer, I aim to maximize human potential and create an exciting future.

In my current role, I work as an SRE with a deep understanding of backend implementation, engaging in a wide range of activities from infrastructure to server tuning, improving development experience, and enhancing organizational productivity.

## Strengths

- Development related to backend and infrastructure
- Infrastructure as Code
- Automation of operations

## Areas of Improvement

- Frontend development
- Implementation and development of native mobile applications

## Work Preferences

### Working Style

- Full remote work

### Job Content

- Backend development
- SRE duties (improving site reliability, promoting automation, etc.)
- Infrastructure setup and operations
- Utilizing and implementing new technologies such as generative AI

### Key Points

- Corporate culture that emphasizes documentation and asynchronous communication
- Striving for a balance between development speed and stability
- Contributing to service development that makes people's lives more convenient
- Actively pursuing and incorporating the latest technological trends

## Preferred Contract Type for Side Jobs

- Commission contract

## Awards

### 2021 MVP Award | Smart Shopping Inc.

Received MVP award for the most outstanding employee in 2021.

Evaluation Points:

- High motivation and ownership in improving the development environment
- Actively addressing customer and operational issues
- Proposing and implementing solutions for building an ideal SRE team

### 2023 Findy Team+ Award

Received for achieving significant improvements in developer productivity and four keys metrics through DevOps promotion.

## Publications

- [Local Development Environment for Microservices in Sync with Kubernetes Clusters](https://tech.smartshopping.co.jp/k8s_microservice)
- [Running Playwright with AWS Lambda Container Image](https://tech.smartshopping.co.jp/lambda-container-playwright)
- [Using Salesforce Bulk API from Go](https://tech.smartshopping.co.jp/salesforce_bulk_go)
- [Transitioned from Backend Engineer to SRE](https://www.biosugar0.com/posts/2021/12/to-sre/)
- [Started Measuring and Tracking Toil](https://tech.smartshopping.co.jp/measure-toil)
- [Transition to Telepresence2](https://tech.smartshopping.co.jp/to-telepresence2)
- [Re-establishing the SRE Team and Creating Mission, Vision, and Values](https://tech.smartshopping.co.jp/ss-new-sre)
- [SRE Team Faces DevOps and Accelerates Development](https://zenn.dev/biosugar0/articles/sre-implements-devops)

## Other

- [Interview with an Engineer Who Supported Product Development from the Start: The Appeal of Doing SRE at Smart Shopping](https://www.wantedly.com/companies/smartshopping/post_articles/513695)
