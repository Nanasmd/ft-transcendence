# ft-transcendence

# 🚀 Guidelines for ft_transcendence

## 🔀 Branch workflow
Please follow these steps:
1. Create a new branch from the master and name it like: _yourname_branchname_
2. Work on your feature
3. Create a pull request in Github when finished
4. Wait for a review from another team member
5. Merge your branch back into the master


## ⚠️ Issues & ToDo
### New issue/ToDo
When you encounter a problem or missing feature in the code that you can't solve right away, follow these steps:
1. Create an issue in Github
2. Write a clear description of the issue and how to reproduce it (make sure that a team member can start fixing the issue without your help)
3. Add a tag with the type of issue (bug, improvement, feature, etc.)

### Fixing an issue
When you start working on an issue:
1. Assign yourself to the issue, so everyone knows you're working on it
2. Follow the branch workflow
3. Link the issue to the created pull request so it's closed when the pr is merged

## Commit Message:
Your commit messages should follow this pattern:

**<type>(FRONT | BACK | FULL): commit message//<login>**

- `<type>` should be either `feat` (for features) or `fix` (for bug fixes).
- `<scope>` should include `FRONT`, `BACK` or `FULL`.
- `<name>` is a brief, descriptive name for your commit.
- `<login>` to identify yourself

Example commit message:

**feat(FRONT): implement new feature//frgojard**

## Features

Ft_transcendance is a single-page application which includes a real-time multiplayer game of pong and a live chat.

### Web

• Major module: Use a Framework as backend.
In this major module, you are required to utilize a specific web framework for your
backend development, and that framework is Django .

• Minor module: Use a database for the backend -and more.
The designated database for all DB instances in your project is PostgreSQL .
This choice guarantees data consistency and compatibility across all project components and may be a prerequisite for other modules, such as the backend Framework module.

• Major module: Store the score of a tournament in the Blockchain.
This Major module focuses on implementing a feature within the Pong website to store tournament scores securely on a blockchain. It is essential to clarify that for development and testing purposes, we will utilize a testing blockchain environment.
The chosen blockchain for this implementation is Ethereum , and Solidity will be the programming language used for smart contract development.
◦ Blockchain Integration: The primary goal of this module is to seamlessly integrate blockchain technology, specifically Ethereum , into the Pong website.
This integration ensures the secure and immutable storage of tournament scores, providing players with a transparent and tamper-proof record of their gaming achievements.
◦ Solidity Smart Contracts: To interact with the blockchain, we will develop Solidity smart contracts. These contracts will be responsible for recording, managing, and retrieving tournament scores.
◦ Testing Blockchain: As mentioned earlier, a testing blockchain will be employed for development and testing purposes. This ensures that all blockchainrelated functionalities are thoroughly validated without any risks associated with a live blockchain.
◦ Interoperability: This module may have dependencies on other modules, particularly the Backend Framework module. Integrating blockchain functionality might necessitate adjustments in the backend to accommodate interactions with the blockchain.

By implementing this module, we aim to enhance the Pong website by introducing a blockchain-based score storage system. Users will benefit from the added layer of security and transparency, ensuring the integrity of their gaming scores. The module emphasizes the use of a testing blockchain environment to minimize risks associated with blockchain development.

### Cybersecurity

These cybersecurity modules are designed to bolster the security posture of the project, with the major module focusing on robust protection through Web Application Firewall (WAF) and ModSecurity configurations and HashiCorp Vault for secure secrets management. The minor modules complement this effort by adding options for GDPR compliance, user data anonymization, a ccount deletion, two-factor authentication (2FA), and JSON Web Tokens (JWT), collectively ensuring the project’s commitment to data protection, privacy, and authentication security.

• Major module: Implement WAF/ModSecurity with Hardened Configuration and HashiCorp Vault for Secrets Management.
In this major module, the objective is to enhance the security infrastructure of the project by implementing several key components. Key features and goals include:
◦ Configure and deploy a Web Application Firewall (WAF) and ModSecurity
with a strict and secure configuration to protect against web-based attacks.
◦ Integrate HashiCorp Vault to securely manage and store sensitive information,
such as API keys, credentials, and environment variables, ensuring that these
secrets are properly encrypted and isolated.
This major module aims to bolster the project’s security infrastructure by implementing robust security measures, including WAF/ModSecurity for web application
protection and HashiCorp Vault for secrets management to ensure a safe and secure
environment.

• Minor module: GDPR Compliance Options with User Anonymization, Local Data Management, and Account Deletion.
In this minor module, the goal is to introduce GDPR compliance options that allow users to exercise their data privacy rights. Key features and objectives include:
◦ Implement GDPR-compliant features that enable users to request anonymization of their personal data, ensuring that their identity and sensitive information are protected.
◦ Provide tools for users to manage their local data, including the ability to view, edit, or delete their personal information stored within the system.
◦ Offer a streamlined process for users to request the permanent deletion of their accounts, including all associated data, ensuring compliance with data protection regulations.
◦ Maintain clear and transparent communication with users regarding their data privacy rights, with easily accessible options to exercise these rights.
This minor module aims to enhance user privacy and data protection by offering GDPR compliance options that empower users to control their personal information and exercise their data privacy rights within the system.
If you are not familiar with the General Data Protection Regulation (GDPR), it is essential to understand its principles and implications, especially regarding user data management and privacy. The GDPR is a regulation that aims to protect the personal data and privacy of individuals within the European Union (EU) and the European Economic Area (EEA). It sets out strict rules and guidelines for organizations on how they should handle and process personal data.
To gain a better understanding of the GDPR and its requirements, it is highly recommended to visit the official website of the European Commission on data protection
. This website provides comprehensive information about the GDPR, including its principles, objectives, and user rights. It also offers additional resources to delve deeper into the topic and ensure compliance with the regulation.
If you are unfamiliar with the GDPR, please take the time to visit the provided link and familiarize yourself with the regulations before proceeding with this project.

• Major module: Implement Two-Factor Authentication (2FA) and JWT.
In this major module, the goal is to enhance security and user authentication by introducing Two-Factor authentication (2FA) and utilizing JSON Web Tokens (JWT). Key features and objectives include:
◦ Implement Two-Factor Authentication (2FA) as an additional layer of security for user accounts, requiring users to provide a secondary verification method, such as a one-time code, in addition to their password.
◦ Utilize JSON Web Tokens (JWT) as a secure method for authentication and authorization, ensuring that user sessions and access to resources are managed securely.
◦ Provide a user-friendly setup process for enabling 2FA, with options for SMS codes, authenticator apps, or email-based verification.
◦ Ensure that JWT tokens are issued and validated securely to prevent unauthorized access to user accounts and sensitive data.
This major module aims to strengthen user account security by offering Two-Factor Authentication (2FA) and enhancing authentication and authorization through the use of JSON Web Tokens (JWT).

### Pong Game Features

The game of Pong features:

- TBA

### Other Features

TBA


## Team work 💪

This project was a team effort. You can checkout the team members here:

-   **Sel-maar**
    -   [Github](///)
    -   [LinkedIn](///)
    -   [42 intra](https://profile.intra.42.fr/users/sel-maar)
-   **Frgojard**
    -   [Github](///)
    -   [LinkedIn](///)
    -   [42 intra](https://profile.intra.42.fr/users/frgojard)
-   **Mvorslov**
    -   [Github](///)
    -   [LinkedIn](///)
    -   [42 intra](https://profile.intra.42.fr/users/mvorslov)
-   **Aclement**
    -   [Github](///)
    -   [LinkedIn](///)
    -   [42 intra](https://profile.intra.42.fr/users/aclement)
-   **Nasamadi**
    -   [Github](https://github.com/Nanasmd)
    -   [LinkedIn](///)
    -   [42 intra](https://profile.intra.42.fr/users/nasamadi)


