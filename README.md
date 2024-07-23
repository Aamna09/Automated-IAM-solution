# Automated-IAM-solution for employee onboarding using Microsoft 365 and Azure

## Description
This project is an automated Identity and Access Management (IAM) solution for employee onboarding process designed to streamline user identity management and access control using Microsoft 365 and Azure. It leverages Microsoft Forms for data collection, Power Automate for workflow automation, and Azure AD for identity and access management.

## Features
- Automated user account creation and provisioning
- Role-based access control
- Group assignments based on department
- Secure and efficient user identity management

## Technologies Used
- Azure AD
- Microsoft Forms
- Power Automate

## Microsoft Forms

### Employee Onboarding Form
This form is used to capture essential information from new employees during the onboarding process. Follow the steps below to recreate the form:

1. Go to [Microsoft Forms](https://forms.office.com/).
2. Create a new form and add the following fields:
   - **Full Name** (Text)
   - **Email Address** (Text)
   - **Department** (Choice)
   - **Position** (Text)
   - **Start Date** (Date)

Refer to the `forms/employee_form.json` file for the detailed structure.

## Automated Workflow

### Employee Onboarding Automated Workflow
This repository contains an automated workflow for employee onboarding, which is implemented using Power Automate. The workflow is provided as a zipped file for easy import into your Power Automate environment.

## Setup Instructions
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/Aamna09/Automated-IAM-solution.git
   cd Automated-IAM-solution
