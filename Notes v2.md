## Introduction

**Name:** Blain  
**Role:** Apprentice DevOps Engineer

### Key Learnings:

- Gaining proficiency in working within technical environments.
- Developing effective communication across varying levels of technical knowledge.
- Strengthening collaborative programming skills.
- Expanding understanding and use of cloud technologies.

### Achievements:

- Successfully contributed to production deployments.
- Played a role in building large repositories to enhance collaboration and modularity in code.
- Supported AWS account and environment administration, including service evaluation to meet organizational needs.
- Helped deploy Terraform modules to automate infrastructure provisioning.

---

## 1. Organizational Culture

### Mindsets:

- **Outcome vs. Activity Driven:**
    
    - **Outcome Driven:** Emphasis on achieving specific results to drive innovation and efficiency.
    - **Activity Driven:** Focusing primarily on completing tasks, which can lead to less meaningful output.
- **Collaboration vs. Silos:**
    
    - **Collaboration:** Encouraging teamwork and open communication to foster innovation and problem-solving.
    - **Silos:** Isolated departments hinder communication and slow progress.
- **Accountability, Trust, and Empowerment:**
    
    - **Accountability:** Maintaining responsibility to drive excellence.
    - **Trust:** Creating a positive environment for initiative and effective collaboration.
    - **Empowerment:** Promoting ownership and decision-making to increase engagement and innovation.

### Current Culture at JD:

- There is a tendency toward isolated work, making visibility across the company and departments difficult, which poses challenges when identifying key contacts.
- A risk-averse mindset, often favoring established, reliable solutions over innovative approaches.
- This cultural stance affects response times to issues and can influence the frequency of issue occurrence.
- Tools like Git Blame and Audit Logs promote accountability, used not for punishment but for continuous improvement.
- A mix of outcome- and activity-driven approaches is employed, focusing on completing smaller tasks to achieve larger goals, with feedback loops to identify areas for improvement.

---

## 2. Data Ethics

### Key Points:

- **Legislation:**
    - GDPR (General Data Protection Regulation)
    - HIPAA (US law)
    - Personal Data Protection Act (PDPA): Governs the collection, use, and disclosure of personal data in Singapore.
    - The organization provides regular updates and training on data protection.

#### Ethical Use of Customer Data

1. **Transparency and Consent:** Clear communication and obtaining user consent for data collection and usage.
2. **Data Minimization:** Only collecting data that is necessary for the task at hand.
3. **Right to Access and Erasure:** Providing individuals with access to their data and the ability to request its deletion.
4. **Security Measures:** Implementing strong data protection practices to safeguard personal information.

#### Relevance to AI and ML

1. **Data Quality and Bias:** Ensuring high-quality, unbiased data in machine learning models.
2. **Algorithmic Transparency:** Providing explanations for AI decision-making processes.
3. **Privacy by Design:** Integrating privacy protections from the initial stages of system development.
4. **Impact Assessments:** Conducting risk assessments to identify and mitigate potential issues related to data use.

#### Practical Steps for DevOps

1. **Compliance Automation:** Automating tasks to ensure compliance with data protection regulations.
2. **Secure Infrastructure:** Strengthening security measures to protect data and infrastructure.
3. **Data Anonymization:** Protecting personal data, especially in development environments.
4. **Continuous Monitoring:** Implementing real-time monitoring to quickly detect and respond to security breaches.
5. **Training and Awareness:** Staying up-to-date on data protection laws and best practices through training and ongoing education.

---

## 3. Problem Solving

### Techniques:

- **Computational Thinking:**
    
    - Decomposition
    - Abstraction
    - Pattern Recognition
    - Algorithmic Thinking
- **Brainstorming:** Exploring a variety of ideas and potential solutions.
    
- **Root Cause Analysis:**
    
    - Defining the problem
    - Collecting data
    - Identifying root causes
    - Developing preventive and corrective solutions
    - Creating actionable strategies
    - Monitoring and validating the implemented solution

### Example at JD:

- **Security Improvements:**
    - Implemented security enhancements using scanning tools.
    - Employed AWS vulnerability scans on resources to identify potential security issues.
    - Planned and aligned configurations with security requirements.
    - Added infrastructure code scanning to repositories to improve security posture.

---

## 4. The Profession in Context

### Example: Setting Up SSO with Microsoft Entra ID (Azure AD) as Part of a Sprint

- **Sprint Planning:**
    
    - During sprint planning, the need to implement Single Sign-On (SSO) with Microsoft Entra ID was identified to streamline authentication processes and enhance security.
- **Identifying Requirements:**
    
    - Collaborated with stakeholders to gather requirements and determine the benefits of integrating SSO with Microsoft Entra ID for the organization.
    - Assessed existing authentication methods and outlined necessary changes to support SSO.
- **Research and Planning:**
    
    - Conducted research on best practices for SSO integration with Microsoft Entra ID (Azure AD) and Octopus Deploy.
    - Developed a comprehensive implementation plan, taking into account necessary configurations, security considerations, and potential challenges.
- **Configuration and Testing:**
    
    - Configured Microsoft Entra ID and Octopus Deploy to enable SSO functionality.
    - Tested the configuration in a private instance using an individual Entra ID account, transitioning to the JD domain after successful validation.
    - Resolved issues during the testing phase and documented key findings.
- **Documentation and Training:**
    
    - Created in-depth documentation covering the SSO setup process, configuration steps, and troubleshooting guidelines.
- **Monitoring and Support:**
    
    - Monitored the SSO implementation post-deployment to ensure its reliability and security.
    - Provided ongoing support to users, addressing any questions or issues that arose.

---

## 5. Tooling and Technology

### Evaluation Process:

- The right tools are identified based on tasks that need to be accomplished, selecting the best and most applicable solution for each scenario.
- Testing is conducted in private or test environments to evaluate solutions.
- Participation in forums and online discussions is encouraged to gauge the suitability of tools.
- Frequent webinars are attended to stay up-to-date with new technologies.
- Demonstrations of new tools or platforms are shared with teams and recorded for reference.

---

## 6. Continuous Learning and Development

### Activities:

- Pursuing relevant certifications to strengthen skills.
- Reinforcing knowledge through teaching and guiding team members, explaining decisions to support team growth.
- Regularly reading about new tools and technologies to stay current.
- Engaging in side projects for both personal development and to apply new technologies in practice.
- Working on personal projects that leverage the same CI/CD platforms as those used at JD, providing additional exposure to platform intricacies.

### Impact on Work:

- Applied Kubernetes knowledge to resolve cluster issues.
- Initiated the Terraforming of the Rancher cluster to improve management and deployment.
- Personal side projects highlighted edge cases and intricacies in tools, deepening practical knowledge and improving overall efficiency.

---

## 7. Peer Review

### Importance:

- Peer reviews help catch missed details and expand expertise across the team.
- Collaborative commits and ticket reviews enhance collective learning and capabilities.
- Feedback provides insights into areas that can be improved or automated.

---

## 8. Communicating and Sharing Knowledge

### Practices:

- Writing clear, self-explanatory code and adding necessary comments to make the codebase easier to maintain.
- Creating documentation that assumes future maintainers may have varying levels of expertise.
- Engaging in whiteboarding and brainstorming sessions to explore ideas collaboratively.
- Ensuring written communication is professional and clear, especially when documenting technical processes.

### Example:

- Developed a Terraform module to set up infrastructure for an SFTP server on AWS. This module serves as a template for future deployments, enabling quick and easy configuration adjustments for different environments (Dev, Test, Prod).
