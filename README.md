# GitHub Actions CI/CD Setup

## Description
As applications scale, ensuring quality and consistency before merging code into critical branches becomes essential. Continuous Integration (CI) and Continuous Deployment (CD) practices help automate testing and deployment, streamlining these processes.

This project implements a **CI/CD pipeline** using **GitHub Actions**, automating **Cypress component testing** and **deployment to Render**, ensuring smooth, efficient workflows.

## Features
- **Automated Cypress Component Testing**: Runs Cypress tests automatically when a **Pull Request (PR)** is made to the `develop` branch.
- **Automated Deployment**: Deploys the application to **Render** when code is merged from `develop` to `main`.
- **Quality and Consistency**: Guarantees that only tested and validated code is merged into the `main` branch, improving code reliability.

## Workflow Overview
1. **Cypress Testing**: On each PR to `develop`, Cypress tests run to validate the functionality of components.
2. **Deployment to Render**: Once code is merged from `develop` to `main`, the pipeline automatically deploys the latest version to **Render**, ensuring a seamless update process.

## Benefits
- Streamlined testing and deployment process.
- Consistent and reliable deployments.
- Saves time and reduces manual errors during the integration and deployment stages.

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

2. **Set Up GitHub Actions**:

  -Install dependencies
          ``` npm install```
  -Run Cypress Tests
           ``` npm run test```

   **Deploy to Render Workflow 
   
   - Deploy to render


4. **Testing the Workflow**:
   - Create a new feature branch and push changes.
   - Open a **Pull Request** to the `develop` branch to trigger the Cypress tests.


## Contribution:
- **Fork the repository**.


## License:
This project is licensed under the **MIT License**.

## Contact
For any inquiries, feel free to reach out via GitHub Issues or Discussions.

