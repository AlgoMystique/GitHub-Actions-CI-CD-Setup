# GitHub Actions CI/CD Setup

## Description:
As applications scale and develop, software engineers aim to ensure quality and consistency before merging code into critical branches. Continuous Integration (CI) and Continuous Deployment (CD) are essential practices that automate testing and deployment processes. 

This project sets up a CI/CD pipeline using **GitHub Actions** to automate **Cypress component testing** and **deployment to Render**.

## Features:
- **Automated Cypress component testing** when a Pull Request (PR) is made to the `develop` branch.
- **Automated deployment** when code is merged from `develop` to `main`.
- **Ensures consistency and quality** before merging code into the main branch.

## Technologies Used:
- **GitHub Actions** – Automates testing and deployment.
- **Cypress** – Runs component tests to validate UI functionality.
- **Render** – Hosts and deploys the application.

## Setup and Installation:
### Prerequisites
- Node.js installed
- Cypress installed (`npm install cypress --save-dev`)
- A GitHub repository with **Actions enabled**
- A Render account for deployment

### Steps to Set Up CI/CD:
1. **Clone the Repository**
   ```
   git clone 
   cd 
   npm install
   ```

2. **Set Up GitHub Actions**

  -Install dependencies
          ``` npm install```
  -Run Cypress Tests
           ``` npm run test```

   **Deploy to Render Workflow 
   
   - Deploy to render


4. **Testing the Workflow**
   - Create a new feature branch and push changes.
   - Open a **Pull Request** to the `develop` branch to trigger the Cypress tests.


## Contribution
- **Fork the repository**.


## License
This project is licensed under the **MIT License**.

## Contact
For any inquiries, feel free to reach out via GitHub Issues or Discussions.

