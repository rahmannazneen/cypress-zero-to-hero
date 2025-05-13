# 🚀 Cypress Setup Guide

This guide will help you set up Cypress in your JavaScript-based project from scratch.

---

## ✅ Prerequisites for Cypress Installation

### 1. Node.js and npm

- Cypress runs on Node.js, so you **must have Node.js and npm installed**.
- **Recommended:** Node.js **version 20** or the **latest LTS version**.
- Check if installed using the following commands:

```
node -v
npm -v
```



### 2. A Code Editor

You will need a code editor to work with Cypress. Some popular editors include:

- **Visual Studio Code**
- **WebStorm**

### 3. Windows PowerShell

After installing Node.js and npm, follow these steps to set up Cypress:

---

## ⚙️ Setting Up Cypress in PowerShell

### 1. Open PowerShell

- Press the Windows icon and choose **Windows PowerShell**.

### 2. Navigate to Your Desired Drive
You can choose the drive where you want to store your Cypress project. 

### 3. Create a New Project Directory
Create a new folder for your Cypress project by typing the following command:

```
mkdir cypress-project

```

### 4. Navigate to the Project Directory
Go into your newly created directory:
```
cd .\cypress-project\
```
### 5. Initialize a New npm Project
Now, initialize a new npm project by running:
```
npm init -y
```
This will create a package.json file in your project.

### 6. Install Cypress
Install Cypress as a development dependency:
```
npm install cypress --save-dev
```


### 7. Open Cypress
Once Cypress is installed, open the Cypress Test Runner:
```
npx cypress open
```

---

# 🎉 Cypress Interface
If everything is set up correctly, you should see the Cypress interface pop up, allowing you to start writing your tests.

![Alt Text](https://github.com/user-attachments/assets/6cd6d868-a4e6-4e4c-9e60-c6cdf01cc82f)










