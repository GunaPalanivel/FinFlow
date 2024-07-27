# Fin Flow - A Fintech Bank Application

![Project Logo](/screenshots/Dashboard.jpg)

Fin Flow is a financial SaaS platform developed with Next.js, offering users seamless connectivity to multiple bank accounts, real-time transaction monitoring, fund transfers, and comprehensive financial management capabilities.

## Table of Contents

- [Introduction](#introduction)
- [Links](#links)
- [Team Members](#team-members)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Quick Start](#quick-start)
- [Screenshots](#screenshots)
- [Conlusion](#conclusion)

## Introduction

Fin Flow provides a modern solution for efficient financial management. Leveraging Next.js, TypeScript, and a robust tech stack including Appwrite, Plaid, and Dwolla, Fin Flow ensures secure authentication, seamless bank integration, and intuitive user experience.

## Links

- [Figjam Flow Diagram](https://www.figma.com/board/GC5JpNbFHa7gSyyD5I7MRK/Fin-Flow-logical-diagram-flow?node-id=0-1&t=sMwNxjOCCi5qEfd7-1)

## Team Members

- [Guna Palanivel](https://www.linkedin.com/in/guna-palanivel/)
- [Gokul S](https://www.linkedin.com/in/gokulselvaraj4/)
- [Bharani V](https://www.linkedin.com/in/bharani-v-20720b276/)

## Tech Stack

- [**Next.js**:](https://nextjs.org/)

  - Provides server-side rendering for enhanced performance and SEO optimization.
  - **Usage**: Next.js is the primary framework utilized for server-side rendering (SSR) in Fin Flow, providing enhanced performance and SEO optimization.
  - **Benefits**: Its SSR capabilities ensure faster loading times and improved search engine visibility, contributing to a better user experience.

- [**TypeScript**:](https://www.typescriptlang.org/)

  - Ensures type safety and code reliability throughout the development process.
  - **Usage**: TypeScript is employed extensively throughout the development process of Fin Flow, ensuring type safety and code reliability.
  - **Benefits**: By enforcing strict typing, TypeScript reduces the likelihood of runtime errors and enhances code maintainability, especially in large codebases.

- [**Appwrite**:](https://appwrite.io/)

  - Enables secure user authentication and data management for the platform.
  - **Usage**: Appwrite serves as the backend solution for Fin Flow, handling user authentication and data management tasks.
  - **Benefits**: With Appwrite, Fin Flow ensures secure user authentication processes and efficient management of user data. Additionally, its comprehensive features, including database management and file storage, contribute to the platform's reliability.

- [**Plaid**:](https://plaid.com/)

  - Facilitates seamless integration with multiple bank accounts, ensuring real-time transaction updates.
  - **Usage**: Plaid integration in Fin Flow facilitates seamless connections with multiple bank accounts, enabling real-time transaction updates.
  - **Benefits**: By leveraging Plaid's robust APIs, Fin Flow empowers users with comprehensive insights into their financial activities across various accounts. This integration enhances user engagement and fosters trust in the platform.

- [**Dwolla**:](https://www.dwolla.com/)

  - Powers fund transfer functionalities, allowing users to securely transfer funds to other accounts.
  - **Usage**: Dwolla powers fund transfer functionalities securely within Fin Flow.
  - **Benefits**: With Dwolla, users can securely transfer funds to other accounts, leveraging its reliable payment processing capabilities. Dwolla's features, such as its ACH transfer system, ensure smooth and secure transactions for users.

- [**React Hook Form**:](https://react-hook-form.com/)

  - Offers a robust solution for form management, enhancing user interaction.
  - **Usage**: React Hook Form is utilized in Fin Flow for efficient and robust form management.
  - **Benefits**: Its lightweight nature and built-in validation capabilities enhance user interaction by providing a seamless form-filling experience. React Hook Form contributes to improved usability and reduces development time by simplifying form handling logic.

- [**Zod**:](https://zod.dev/)

  - Provides schema validation for data integrity and security.
  - **Usage**: Zod is integrated into Fin Flow for schema validation, ensuring data integrity and security.
  - **Benefits**: By validating user input against predefined schemas, Zod helps prevent data inconsistencies and vulnerabilities. Its straightforward API and runtime validation capabilities enhance the overall reliability of the application.

- [**TailwindCSS**:](https://tailwindcss.com/)

  - Enhances UI design with modern styling and responsiveness.
  - **Usage**: TailwindCSS is employed in Fin Flow to enhance UI design with modern styling and responsiveness.
  - **Benefits**: By using utility classes, TailwindCSS allows for rapid UI development and customization, resulting in a sleek and visually appealing interface. Its mobile-first approach ensures consistent user experiences across various devices, improving accessibility and user satisfaction.

- [**Chart.js**:](https://www.chartjs.org/)

  - Enables visualization of financial data for better insights.
  - **Usage**: Chart.js is integrated into Fin Flow for visualizing financial data in interactive and visually appealing charts.
  - **Benefits**: Its extensive chart types and customization options enable users to gain insights into their finances effectively. Chart.js enhances data visualization capabilities within the application, facilitating informed decision-making and enhancing user engagement.

- [**ShadCN**:](https://ui.shadcn.com/)

  - Offers UI components for building a sleek and user-friendly interface.
  - **Usage**: ShadCN provides UI components utilized in Fin Flow for building a sleek and user-friendly interface.
  - **Benefits**: By leveraging ShadCN's UI components, Fin Flow ensures consistency in design and a polished user interface. ShadCN's components offer pre-styled elements that streamline UI development, reducing development time and effort while maintaining design coherence.

## Open Source Acknowledgements

This project utilizes the following open-source tools and libraries:

- **[Next.js](https://nextjs.org/)**: A React framework that enables server-side rendering and static site generation.
- **[TypeScript](https://www.typescriptlang.org/)**: Provides type safety and enhances code maintainability.
- **[Appwrite](https://appwrite.io/)**: An open-source backend platform used for user authentication and database management.
- **[Plaid’s open-source SDKs](https://github.com/plaid)**: Plaid is a service that connects applications to users’ bank accounts. It enables developers to access users' bank account data, including balances, transactions, and account details.
- **[Dwolla](https://github.com/Dwolla)**: Dwolla is a platform that facilitates ACH (Automated Clearing House) transfers, enabling secure and efficient bank-to-bank payments.
- **[React Hook Form](https://react-hook-form.com/)**: Manages form state with easy validation and performance.
- **[Zod](https://zod.dev/)**: Validates schema with TypeScript support for improved data integrity.
- **[TailwindCSS](https://tailwindcss.com/)**: Provides utility-first styling for modern, responsive design.
- **[Chart.js](https://www.chartjs.org/)**: For rendering interactive charts and graphs.

  **We acknowledge and appreciate the contributions of these open-source projects to our work.**

## Features

- **Authentication**: Implements ultra-secure SSR authentication with proper validations and authorization for enhanced security.
- **Bank Integration**: Integrates seamlessly with Plaid to connect multiple bank accounts, providing users with a holistic view of their finances.
- **Home Page**: Displays a comprehensive overview of user accounts, including total balance, recent transactions, and spending insights.
- **My Banks**: Allows users to view the complete list of connected banks along with respective balances and account details.
- **Transaction History**: Provides pagination and filtering options for viewing transaction history across different banks.
- **Real-time Updates**: Reflects changes across all relevant pages instantly upon connecting new bank accounts, ensuring up-to-date information for users.
- **Funds Transfer**: Enables users to transfer funds securely using Dwolla, with required fields and recipient bank ID for smooth transactions.
- **Responsiveness**: Ensures seamless adaptation to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.

## Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- **Git**

```link
https://git-scm.com/downloads
```

- **Node.js**

```link
https://nodejs.org/en/download/
```

- **npm (Node Package Manager)**[ Install npm globally using the following command:]

```bash
npm install -g npm
```

### Installation [To run the project locally]

Clone the repository

```bash
git clone https://github.com/GunaPalanivel/FinFlow.git
```

Navigate to the project directory

```bash
cd FinFlow
```

Install the dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

## User Account Creation with Appwrite

In this section, the application leverages Appwrite, an open-source backend server, to simplify the process of creating and managing user accounts for web and mobile applications.

### Overview

Appwrite offers a variety of features, including user authentication, database management, file storage, and more, making it a powerful tool for developers. The application utilizes Appwrite's Email Password Session feature to allow users to create secure accounts using their email addresses and passwords.

### Key Features

- Simplifies user account management for web and mobile applications.
- Offers secure user authentication through email and password sessions.
- Provides comprehensive documentation and a user-friendly interface for easy integration and development.
- Supports multiple programming languages and frameworks, ensuring versatility and accessibility.

## Dwolla Integration for Payment Processing

Once users have created their accounts, the application integrates with Dwolla, an online payment platform that facilitates secure fund transfers.

### Overview

Dwolla offers a reliable way for users to send, receive, and request money, making it an ideal choice for handling financial transactions within the application. The application generates unique Dwolla customer URLs and IDs for each user to establish a secure connection between the application and Dwolla.

### Key Features

- Facilitates secure fund transfers through Dwolla's platform.
- Generates unique Dwolla customer URLs and IDs for seamless connectivity.
- Provides a reliable solution for sending, receiving, and requesting money within the application.

## Plaid Link Integration for Bank Account Connection

To offer users a comprehensive financial management experience, the application integrates with Plaid Link, a service that enables secure connections between bank accounts and third-party applications.

### Overview

Plaid Link simplifies the process of accessing real-time transaction data and balance updates, empowering users with valuable financial insights. Users can securely link their bank accounts to the application through Plaid Link, facilitating the exchange of data between Plaid and the platform.

### Key Features

- Enables secure connections between bank accounts and the application.
- Simplifies access to real-time transaction data and balance updates.
- Provides a seamless user experience for managing finances within the application.

## Fund Transfer Process

The application provides users with a seamless fund transfer process, leveraging the integrations with Appwrite, Dwolla, and Plaid.

### Overview

Users initiate the fund transfer process by submitting a form, providing the recipient's public bank account ID obtained from the Appwrite Bank Collection. The application retrieves bank details from the collection, initiates a fund transfer through Dwolla, and updates transaction history in the Appwrite "Transaction" collection upon successful completion.

### Key Features

- Initiates fund transfers securely through Dwolla.
- Retrieves bank details from the Appwrite Bank Collection.
- Updates transaction history for transparency and accountability.

## Screenshots

Here are some screenshots of the Fin Flow application:

- **Dashboard**: Provides an overview of user accounts, total balance, recent transactions, and spending insights.

  ![Project Logo](/screenshots/Dashboard.jpg)

- **My Banks**: Displays a list of connected banks with respective balances and account details.

  ![Project Logo](/screenshots/My%20Banks.jpg)

- **Payment Transfer**: Allows users to transfer funds securely using Dwolla, with required fields and recipient bank ID for smooth transactions.

  ![Project Logo](/screenshots/Payment%20Transfer.jpg)

- **Transaction History**: Provides pagination and filtering options for viewing transaction history across different banks.

  ![Project Logo](/screenshots/Transaction%20History.jpg)

## Contributing

We welcome contributions from the community to make this project even better! To get started, please follow these steps:

1. **Fork the Repository**: Click the "Fork" button at the top right corner of this page to create a copy of the repository in your GitHub account.
2. **Clone Your Fork**: Clone your forked repository to your local machine.

   ```bash
   git clone https://github.com/GunaPalanivel/FinFlow.git
   ```

   ```bash
   cd FinFlow
   ```

3. **Create a New Branch**: Create a new branch for your feature or bug fix.

   ```bash
   git checkout -b feature-branch
   ```

4. **Make Your Changes**: Implement your changes or additions in the new branch.

5. **Commit Your Changes**: Once your changes are ready, commit them with a descriptive message.

   ```bash
   git commit -m "Add [feature/bug description]"
   ```

6. **Push to Your Branch**: Push the committed changes to your forked repository.

   ```bash
   git push origin feature-branch
   ```

7. **Open a Pull Request**: Navigate to the original repository and open a pull request (PR) from your forked repository. Be sure to provide a clear description of the changes you have made and any additional context that might be helpful for the reviewers.

### Guidelines for Contributing

- **Write Clear Commit Messages**: Use clear and concise commit messages that accurately describe the changes made.
- **Code Style**: Ensure your code follows the project's style guidelines and best practices.
- **Documentation**: Update the documentation if your changes include new features or significant modifications.
- **Tests**: If applicable, write tests for your changes to ensure functionality is maintained and new features work as expected.

### Reviewing and Merging Pull Requests

All contributions will be reviewed by the project maintainers. Feedback and suggestions for improvements may be provided during the review process. Once your pull request has been reviewed and approved, it will be merged into the main branch.

We appreciate your contributions and thank you for helping improve this project!

If you have any questions or need further assistance, feel free to reach out to us by opening an issue in the repository.

Let's continue pushing boundaries and crafting exceptional web experiences together! 💻✨

## Conclusion

By leveraging Appwrite, Dwolla, and Plaid integrations, the application offers users a robust platform for user account management, payment processing, and financial transactions. The seamless integration of these services ensures a secure, efficient, and user-friendly experience for managing finances within the application.

## License

This project is licensed under the [MIT License](LICENSE) - For more details, please visit: [Open Source Initiative License](https://opensource.org/licenses/MIT)

---

---

## This project is not enabled for public use for safety reasons.

### Safety Notice 🚨

**Please note that this project is currently not enabled for public use.** This restriction is in place for the following safety reasons:

- **Data Security**: Ensuring the confidentiality and security of user data is our top priority. Public access could potentially expose sensitive information, risking data breaches or misuse.

- **Feature Integrity**: We are still in the development phase, and some features may not be fully tested or secure. Limiting access helps prevent issues that could arise from incomplete or unverified functionalities.

- **Compliance**: Compliance with legal and regulatory requirements is crucial for financial applications. By restricting access, we can ensure that all necessary measures are in place before a broader release.

- **Quality Control**: We aim to deliver a high-quality and reliable application. Limiting access allows us to focus on improving the project and addressing any issues before making it available to the public.

We appreciate your understanding and patience. If you have any questions or need further information, please feel free to reach out to us by opening an issue in the repository.

```
This readme provides a comprehensive overview of Fin Flow, a financial SaaS platform, emphasizing its technical architecture, features, and integrations. It offers a clear understanding of the project's structure, technology stack, and functionalities, enabling developers and users to grasp its capabilities effectively.
```
