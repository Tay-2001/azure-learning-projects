**Disclaimer:** This repository is intended for educational purposes only. Feel free to explore and learn from the content here, but **please do not directly clone or use this work for commercial purposes** without permission. If you want to use this in your own projects, please respect the [license](LICENSE).

## Purpose
This repository is designed to help others learn how to set up a Virtual Machine in Azure.


This project demonstrates the steps to set up a Virtual Machine (VM) in Azure for the AZ-900 exam preparation.

# Azure Virtual Machine

This repository contains beginner-friendly projects for learning Microsoft Azure.

## Step 1: Set Up Your Repository

1. Log in to GitHub.
2. Go to your profile and click **"Repositories"**, then click **"New"**.
3. Use the following settings:
    - **Repository Name**: `azure-learning-projects` (or any name you like).
    - **Description**: _"A collection of beginner-friendly projects for learning Microsoft Azure."_
    - **Public Repository**: Make it public to showcase your work to potential employers.
    - **Initialize with a README**: Check this box.
4. Click **Create Repository**.

---

## Step 2: Kick Off Your First Project

Let's start with **Azure Virtual Machines Basics (Project #1)**. This is a beginner-friendly way to learn key concepts like provisioning and managing resources in Azure.

### Part 1: What You'll Need

- **Azure Free Account**: If you don't already have one, sign up for an [Azure Free account](https://azure.microsoft.com/en-us/free/) to get $200 in credits.
- **Azure CLI**: Install the Azure CLI on your local machine. Follow the [installation guide](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli).

---

## Part 2: Project Steps

### Step 2.1: Create a Virtual Machine

1. Log in to the [Azure Portal](https://portal.azure.com).
2. Navigate to **Virtual Machines** and click **Create**.
3. Click **"Azure Virtual Machine"** (the first option).
4. This will take you to the setup wizard for creating a virtual machine.

![first page image](https://github.com/Tay-2001/azure-learning-projects/blob/12ffe2f13382a3b4a0dfcd0d11a97f69e74abfa2/Screenshot%202024-11-27%20165818.png)

![first page image](https://github.com/Tay-2001/azure-learning-projects/blob/12ffe2f13382a3b4a0dfcd0d11a97f69e74abfa2/Screenshot%202024-11-27%20165945.png)

### Step 2.2: Fill in the Required Details

- **Subscription**: Choose the free or active subscription available in your account.
  - **What It Means**: This is the billing account where Azure tracks your usage. If you're using a free account, this will be your default free-tier subscription.
  - **Why We Do It**: Azure needs to know which subscription to charge (or not charge, if you're in the free tier).

- **Resource Group**: Create a new resource group or use an existing one (e.g., name it `project`).
  - **What It Means**: A resource group is like a folder that holds all the resources (like VMs, storage, etc.) for a project. Think of it as a way to keep things organized.
  - **Why We Do It**: By using resource groups, you can manage related resources together (e.g., delete them all at once when you're done).

---

## Screenshot of Azure VM Setup

![Azure VM Screenshot](images/vm-setup.png)

_This is an example of the VM setup screen in the Azure portal._

---

Feel free to modify and expand on these steps as needed!



**Note:** This repository is for educational purposes. The aim is to help others learn how to set up a VM in Azure. Please do not copy or clone this repository without understanding the concepts. Instead, use it as a guide for your learning journey. Thanks for respecting my work!
