## Introduction

**Name:** Blain  
**Role:** Apprentice DevOps Engineer

### Key Learnings:

- Working effectively in a technical environment
- Communicating across a range of knowledge levels
- Collaborative programming
- Understanding and utilizing cloud technologies

### Achievements:

- Successfully deployed code into production
- Created large repositories for collaboration and code modularization
- Assisted in administrating AWS accounts and environments, evaluating services to meet organizational needs
- Successfully deployed terraform modules for 

---

## 1. Organizational Culture

### Mindsets:

- **Outcome vs. Activity Driven:**
    - **Outcome Driven:** Prioritize achieving specific results to encourage innovation and efficiency.
    - **Activity Driven:** Focus on completing tasks, which can lead to busywork without meaningful results.
    -
- **Collaboration vs. Silos:**
    - **Collaboration:** Promote teamwork and open communication for greater innovation and problem-solving.
    - **Silos:** Isolated departments hinder communication and slow progress.
- **Accountability, Trust, and Empowerment:**
    - **Accountability:** Ensuring responsibility to drive excellence.
    - **Trust:** Building a positive environment for initiative and effective collaboration.
    - **Empowerment:** Encouraging ownership and decision-making to enhance engagement and innovation.

### Current Culture at JD:

- Isolated culture with poor visibility across the company and departments, making it challenging to identify key contacts.
- Risk-averse, preferring reliable, established solutions over innovative approaches.
- Cultural impact on response times to issues and likelihood of issue occurrence.
- Tools like Git Blame and Audit Logs foster accountability and are used for continuous improvement rather than punishment.
-  JD has a mix of both of these, in order to achieve specific results, we need to focus on competing the smaller tasks to achieve the greater tasks by using feedback to identify where improvements can be made

---

## 2. Data Ethics

### Key Points:

- **Legislation:**
    - GDPR - General Data Protection Regulation
    - HIPAA (US law)
    - **Personal Data Protection Act (PDPA)**: Singapore's PDPA governs the collection, use, and disclosure of personal data by organization
    - company has updates training on DATA PROTECTION

#### Ethical Use of Customer Data

1. **Transparency and Consent**: Clear communication and consent required for data use.
2. **Data Minimization**: Collect only necessary data.
3. **Right to Access and Erasure**: Individuals can access and delete their data.
4. **Security Measures**: Ensure robust data protection.

#### Relevance to AI and ML

1. **Data Quality and Bias**: High-quality, unbiased data is essential.
2. **Algorithmic Transparency**: Ensure AI decisions are explainable.
3. **Privacy by Design**: Integrate privacy from the outset.
4. **Impact Assessments**: Conduct assessments to mitigate risks.

#### Practical Steps for DevOps

1. **Compliance Automation**: Automate data protection compliance tasks.
2. **Secure Infrastructure**: Implement strong security measures.
3. **Data Anonymization**: Protect personal data in development.
4. **Continuous Monitoring**: Detect and respond to breaches quickly.
5. **Training and Awareness**: Stay informed on data protection laws and best practices.

---

## 3. Problem Solving

### Techniques:

- **Computational Thinking:**
    - Decomposition
    - Abstraction
    - Pattern Recognition
    - Algorithmic Thinking
- **Brainstorming:** Methods for exploring ideas and solutions.
- **Root Cause Analysis:**
    - Define the problem
    - Collect data
    - Identify root causes
    - Develop preventive and corrective solutions
    - Create actionable strategies
    - Monitor and confirm the working solution

### Example at JD:

- **Security Improvements:**
    - Using scanning tools for security enhancements.
    - Employing AWS vulnerability scans on our aws resources
    - Planning and aligning configurations with security requirements.
    - Adding infrastructure code scanning to repositories.

---

## 4. The Profession in Context

**Example: Setting Up SSO with Microsoft Entra ID (Azure AD) as Part of a Sprint**

- **Sprint Planning:**
    
    - During sprint planning, identified the need to implement SSO with Microsoft Entra ID to streamline authentication processes and enhance security.

- **Identifying Requirements:**
    
    - Worked with stakeholders to gather requirements and understand the benefits of integrating SSO with Microsoft Entra ID for the organization.
    - Assessed existing authentication methods and determined the necessary changes to support SSO.
- **Research and Planning:**
    
    - Researched integration options and best practices for configuring SSO with Microsoft Entra ID (Azure AD) and Octopus Deploy.
    - Developed a detailed implementation plan, including necessary configurations, security considerations, and potential challenges.
- **Configuration and Testing:**
    
    - Configured Microsoft Entra ID (Azure AD) and Octopus Deploy for SSO integration.
    - Conducted thorough testing on my own private instance using my own entra id account and then was able to  transition the tenant to the jd domain.
    - Identified , resolved any issues encountered during the testing phase and documented findings.
- **Documentation and Training:**
    
    - Created comprehensive documentation detailing the SSO setup process, configuration steps, and troubleshooting guidelines.
    - 
- **Monitoring and Support:**
    
    - Monitored the SSO implementation post-deployment to ensure it functioned correctly and securely.
    - Offered ongoing support to address any issues or questions from users, ensuring the continued reliability of the SSO system.

---

## 5. Tooling and Technology

### Evaluation:

- Identifying the right tools for the job by examining what tasks we need to accomplish and what's the best and most applicable solution to use.
- Testing different solutions using private/test instances
- Participating in forums and online discussions to gauge tool suitability.
- Frequent webinars for showcasing new technologies 
- Demoing new technology or platforms on teams which are recorded for reference

---

## 6. Continuous Learning and Development

### Activities:

- Pursuing certifications.
- Reinforcing knowledge by teaching others, guiding them, and explaining choices to strengthen the team.
- Enjoying reading about new technologies and tools.
- Engaging in side projects for fun and learning.
- Personal projects which use the same ci/cd platform as we use in JD to boost my familiarity with each platform 

### Impact on Work:

- Applied Kubernetes knowledge to solve cluster issues.
- Initiated Terraforming of the Rancher cluster.
- Side projects exposed tool intricacies and potential edge cases, enhancing practical knowledge.

---

## 7. Peer Review

### Importance:

- Peer review helps identify missed details and broadens expertise.
- Collaborative commits and tickets enhance learning and capability.
- Feedback helps to identify, what can be improved or automated if possible

---

## 8. Communicating and Sharing Knowledge

### Practices:

- Writing self-commenting code and adding explanatory comments.
- Creating comprehensive documentation that assumes different maintainers.
- Using whiteboarding and brainstorming sessions.
- Ensuring efficient written communication with professional language and clarity.

### Example:

-I wrote a relatively complex terraform module to set up the infrastructure to set up an sftp server in aws .
This will be used as a template for future deployments where we can use my template and change values and variables where necessary for a quick and easy deployment to the required environment( Dev, Test, Prod)
