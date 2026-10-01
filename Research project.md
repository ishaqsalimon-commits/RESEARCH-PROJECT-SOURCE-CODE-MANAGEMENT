##### RESEARCH PROJECT SOURCE CODE MANAGEMENT

##### Question 1:
How does Git enhance source code management practices in modern software development, and what are its key advantages and challenges compared to other version control systems?
##### Answer:
Git enhances source code management by providing version tracking, distributed development, branching, merging, collaboration, code review, and integration with automated CI/CD pipelines. Its main strengths are speed, flexibility, offline operation, and powerful branching.
Its main challenges are the learning curve, merge conflicts, complex advanced commands, and difficulties with very large binary files.
Compared with centralized systems such as SVN, Git provides greater flexibility for distributed and modern DevOps workflows, which is why it has become a fundamental tool in contemporary software development.

##### Question 2:
How did source code management practices evolve before Git?
##### Answer:
Before Git, source code management evolved from manual backups → local version control → centralized version control → distributed version control. Each stage addressed problems discovered in the previous approach. Git built on the distributed model and combined it with fast branching, merging, strong history tracking, and support for large collaborative projects, making it particularly suitable for modern software development and DevOps workflows.

##### Question 3:
What were the limitations of previous version control systems (VCS) that Git aimed to address?
##### Answer:
Before Git, developers used systems such as CVS, SVN, and BitKeeper to manage source code. Git did not invent version control, but it addressed several limitations that became increasingly important as software projects grew larger and development teams became more distributed. Its distributed architecture, fast local operations, lightweight branching, powerful merging, offline capabilities, and strong data-integrity mechanisms made it particularly suitable for modern software development and DevOps.

##### Question 4:
What are the primary features of Git that differentiate it from other VCS tools?
##### Answer:
The primary features that distinguish Git are its distributed architecture, fast local operations, lightweight branching, powerful merging, offline capabilities, staging area, cryptographic data integrity, and flexible collaboration workflows. These features make Git particularly suitable for modern software development, especially Agile development and DevOps environments where frequent code changes, collaboration, automated testing, and CI/CD are important.

##### Question 5:
How do branching, merging, and repository management in Git improve development workflows?
##### Answer:
Branching allows developers to work independently, merging brings their completed work together, and repository management organizes the project's code and history. Together, these Git features make development more organized, collaborative, and traceable. They are especially useful in DevOps environments, where developers frequently integrate code changes, run automated tests, and deploy applications through CI/CD pipelines.

##### Question 6:
What are the main benefits of using Git for source code management in terms of collaboration, version tracking, and integration with CI/CD pipelines?
##### Answer:
The main benefits of Git are better collaboration, reliable version tracking, and strong integration with CI/CD pipelines. Git allows developers to work in parallel through branches, maintain a detailed history through commits, and automatically connect code changes to build, testing, security, and deployment processes. As a result, Git is an important foundation for modern software development and DevOps practices.

##### Question 7:
How does Git support distributed development teams?
##### Answer:
Git supports distributed development teams through its distributed architecture, local repositories, offline capabilities, branching, remote repositories, code-review workflows, conflict management, and CI/CD integration. These features allow developers in different locations and time zones to work independently while still maintaining a coordinated and traceable software-development process.

##### Question 8:
What are the common challenges or drawbacks developers face when using Git?
##### Answer:
The main drawbacks of Git are its learning curve, merge conflicts, complex branching and history management, risk of mistakes with advanced commands, and challenges with large files and repositories. Most of these challenges can be reduced through proper Git training, clear team workflows, regular commits, meaningful branch naming, code reviews, and careful use of commands such as reset, rebase, and force push.

##### Question 9:
How can these challenges be mitigated through best practices or supplementary tools?
##### Answer:
Git challenges can be mitigated through a combination of good practices and supplementary tools. Teams should use clear branching strategies, meaningful commits, pull requests, protected branches, automated testing, .gitignore, Git LFS for large files, and appropriate IDE or Git-management tools.
For a DevOps team, the most effective approach is to combine Git with code review, CI/CD automation, security scanning, and clear team standards. This creates a workflow that is more consistent, traceable, and less prone to accidental errors.

##### Question 10:
How does Git compare with other popular VCS tools like Subversion (SVN), Mercurial, or Perforce in terms of functionality, performance, user adoption, handling large codebases, and branching models? Compare why Distributed Version Control System (Git) might be preferred to other Version Control Systems in certain environments (banks, game development companies, & hospitals).
##### Answer:
Git's main strengths are its distributed architecture, fast local operations, lightweight branching, powerful merging, extensive ecosystem, and strong integration with CI/CD and DevOps tools.

Compared with SVN, Git provides greater independence from a central server. Compared with Mercurial, Git offers a much larger ecosystem and broader industry adoption. Compared with Perforce, Git is often more convenient for source-code-centric and DevOps workflows, while Perforce can have advantages for extremely large binary-heavy projects.

Therefore, organizations such as banks, hospitals, and software companies may prefer Git when they need distributed development, strong code review, automated CI/CD, and flexible branching. Game development companies with very large binary assets may instead evaluate Git + Git LFS alongside Perforce, depending on their project requirements.

##### Question 11:
What are the specific use cases or scenarios where other VCS might be preferred over Git?
##### Answer:
Git is a strong general-purpose choice, especially for software development, DevOps, cloud applications, and distributed teams. However, SVN can be appropriate for centralized and legacy environments, Mercurial for teams already invested in its distributed workflow, and Perforce for very large binary-heavy projects such as games and visual production.

The important principle is that organizations should choose a VCS based on their technical requirements and existing workflow, rather than simply choosing the most popular tool.

##### Question 12:
How have different organizations or projects implemented Git for source code management?
##### Answer:
Organizations implement Git in different ways, but the common principle is to use Git as a central record of source-code changes while building an appropriate workflow around it. Small teams may need only branches and pull requests, while banks, hospitals, and large enterprises may add access controls, mandatory reviews, security scanning, automated testing, CI/CD, and audit processes.

The flexibility of Git allows the same version-control system to support simple projects as well as complex enterprise and DevOps environments.

##### Question 13:
What lessons can be learned from these case studies regarding successful Git adoption and management?
##### Answer:
The main lesson from successful Git adoption is that Git itself is only part of the solution. Organizations achieve better results when they combine Git with training, clear workflows, appropriate branching strategies, code review, automated testing, security controls, documentation, and CI/CD automation.

For a DevOps team, the goal should not simply be "use Git." The goal is to build a reliable workflow where every code change can be tracked, reviewed, tested, and safely delivered.

##### Question 14:
What are the best practices for managing user access and authentication in SCM tools like Git, and how can multi-factor authentication (MFA) and role-based access control (RBAC) be implemented to ensure secure code repositories?
##### Answer:
Secure Git/SCM management should combine MFA + RBAC + least privilege + protected branches + secure credentials + regular access reviews + monitoring.

MFA primarily answers "Are you really the person logging in?", while RBAC answers "What are you allowed to do?". Using both provides a stronger security model for protecting source-code repositories and the CI/CD systems connected to them.

##### Question 15:
What are the recommended practices for securing repositories hosted on cloud-based platforms like GitHub, GitLab, and Bitbucket, and how does encrypting repositories and using secure communication protocols (SSH vs. HTTPS) prevent unauthorized access?
##### Answer:
Securing GitHub, GitLab, or Bitbucket repositories requires multiple layers of protection rather than relying on encryption alone.

The recommended approach is to combine MFA, RBAC, least privilege, protected branches, secure HTTPS/SSH communication, encryption at rest, secret management, security scanning, audit logging, and backups.

In simple terms:

MFA verifies the user, RBAC controls what they can do, HTTPS/SSH protects communication, encryption protects stored data, and repository policies protect the code itself.

Together, these controls significantly reduce the risk of unauthorized access, credential theft, data interception, and unauthorized source-code modifications.

##### Question 16:
What are the best practices for logging and auditing in SCM to ensure that all repository activities (e.g., commits, merges, pushes) are tracked for security purposes, and how can automated alerts notify teams of suspicious changes?
##### Answer:
Effective SCM auditing requires more than simply running git log. Organizations should combine Git history, platform audit logs, protected branches, centralized logging, SIEM/monitoring, and automated alerts.

The overall security process can be summarized as:

Record → Centralize → Analyze → Alert → Investigate → Respond

This approach helps organizations maintain a reliable record of who made changes, what was changed, when it happened, how it was approved, and whether the activity was authorized.

##### Question 17:
What are the emerging trends in source code management, and how is Git evolving to meet these new demands?
##### Answer:
The future of SCM is moving toward automation, AI-assisted development, DevSecOps, cloud-native infrastructure, GitOps, supply-chain security, and increasingly integrated developer platforms.

Git remains important because its distributed architecture and flexible branching/history model provide a strong foundation for these workflows. However, Git's evolution is not simply about adding more commands to Git itself. Much of the innovation is occurring in the ecosystem around Git, where Git repositories are connected to AI tools, CI/CD, security systems, cloud infrastructure, Kubernetes, and automated deployment platforms.

In modern DevOps, Git is increasingly more than a place to store source code—it can serve as a central source of truth for how software and infrastructure are developed, tested, secured, and delivered.

##### Question 18:
How might advancements in DevOps, continuous integration/continuous deployment (CI/CD), and automation impact the future use of Git?
##### Answer:
The future of Git is likely to be increasingly automated and integrated. DevOps, CI/CD, and automation will make Git a central control point connecting code → testing → security → infrastructure → deployment → monitoring.

For a DevOps engineer, this means learning Git should go beyond commands such as git add, git commit, and git push. It is important to understand how Git connects with CI/CD pipelines, Docker, Kubernetes, Infrastructure as Code, GitOps, security scanning, and automated cloud deployments.

In short, Git is evolving from a version-control tool into a key foundation for automated software delivery and DevOps workflows.

