 # Login Interface Project - Setup Guide

Welcome to the **Login Interface Project**! This project provides a secure and organized interface for managing repositories, searching Google, and using various tools. Follow the steps below to set up and use the program in your Termux environment.

## Prerequisites

1. **Install Termux**:
   - Download and install **Termux** from [F-Droid](https://f-droid.org/packages/com.termux/) or the [Google Play Store](https://play.google.com/store/apps/details?id=com.termux).
   - Open Termux once installed.

2. **Install Dependencies**:
   - Open Termux and run the following commands to update Termux and install necessary packages:

     ```bash
     pkg update && pkg upgrade -y
     pkg install -y git curl wget openssl bash
     ```

---

## Step 1: Clone the Repository

1. Clone the **login-interface** repository from GitHub (replace `yourusername` with your GitHub username):

   ```bash
   git clone https://github.com/MrNova420/login-interface.git
   then once you installed it by using

copy and paste in terminal 

git clone https:hithub.com/MrNova420/login-interface 

Then open it by typing 

cd login-interface 

Next Give execute permissions to the setup script:

copy and oast it in terminal 

chmod +x setup.sh
next
Run the Setup Script

1. Run the setup script to configure the project:

./login-interface.sh

This script will:

Install necessary dependencies.

Clone or update the GitHub repository.

Set up the main menu and options for the project.
 after done you are ready to use and just type 
 
./login-interface.sh 

to start program 
