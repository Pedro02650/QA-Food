# Maestro 🎹

Maestro is the easiest way to automate UI testing for your mobile app.

> **Note**
> **Full documentation for Maestro can be found at [maestro.mobile.dev](https://maestro.mobile.dev)**


<img src="https://user-images.githubusercontent.com/847683/187275009-ddbdf963-ce1d-4e07-ac08-b10f145e8894.gif" />



# Maestro samples

`maestro download-samples` provides a set of flows and apps so that users can quickly set up a maestro test, without having to create an app.

download-samples downloads these files and apps from storage.googleapis.com.

# How to run the project on your machine

This project uses **Maestro Studio** for mobile application testing automation. Follow the steps below to run the tests **locally** and in **headless mode**.

## Prerequisites

- **Node.js**:(https://nodejs.org)
- **Maestro Studio **: (https://maestro.app)
- **Mobile device or emulator/simulator** configured (https://developer.android.com)

## Step 1: Clone the repository

Clone this repository:

git clone https ://github.com/Pedro02650/QA-Food.git

## Step 2: Install dependencies

Install the dependencies with npm:

npm install

## Step 3: Configure the environment

Configure the environment depending on your operating system.

For macOS or Linux:

export ANDROID_HOME=/path/to/android/sdk
export PATH=$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools:$PATH

For Windows:

Set the environment variables in the System > Environment Variables panel: ANDROID_HOME = C:\path\to\android\sdk
Add C:\path\to\android\sdk\platform-tools to Path.

## Step 4: Run the tests locally

macOS / Linux / Windows:

To run the tests locally on a device or emulator, run the command:

npx maestro test

## Step 5: Run the tests in headless mode

macOS / Linux / Windows: To run the tests in headless mode (without a graphical interface), use the command:

npx maestro test --headless

## Contacts

<a href="https://www.linkedin.com/in/pedro-cisne/">
< img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
<a href = "mailto:pedrohpcisne@gmail.com" ><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank">
 </a>
