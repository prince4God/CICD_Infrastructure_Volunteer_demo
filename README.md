# CICD_Infrastructure_Volunteer_demo
This is the demo of a setup that does an automated build/deploy. 

Automated Build and Deploy Demo

This repository demonstrates setting up automated build and deploy using GitHub Actions for a Node.js application.

Table of Contents

    Prerequisites
    Setting Up Automated Build and Deploy
    Customization
    License

Prerequisites

Before proceeding, ensure you have the following:

    Node.js and npm: Ensure Node.js and npm (Node Package Manager) are installed on your machine. 

    GitHub Account: Ensure you have a GitHub account. 

Setting Up Automated Build and Deploy

Follow these steps to set up automated build and deploy for your Node.js application:

    Clone the Repository: Clone this repository to your local machine using git clone.

    Navigate to the Repository: cd into the cloned repository.

    Create a package.json file: Create a package.json file for your Node.js application. You can use the provided package.json template and modify it according to your project.

    Create GitHub Actions Workflow:
        Inside the .github/workflows directory, create a YAML file (e.g., build-deploy.yml).
        Use the provided GitHub Actions Workflow template as a starting point and customize it based on your project's build and deploy requirements.

    Push Changes to GitHub: Commit the package.json and the GitHub Actions workflow file to your repository and push the changes to GitHub.

    Trigger the Workflow: Any subsequent push to the repository's main branch will trigger the GitHub Actions workflow, automating the build and deploy process.

Customization

    Build Script: Modify the "build" script in the package.json to match your application's build process. Update the script to run your specific build command.

    Deployment: In the GitHub Actions workflow, replace the deployment step (Deploy) with the appropriate commands for deploying your application. This could involve deploying to a server, a cloud platform, or any other hosting service.

JUST FOR DEMONSTRATION:  This demo will not build and deploy because there is no source or server url.

License

This demo is provided under the MIT License.
