# 🐾 Pet Store API Testing Project

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWqimV0fZPeeWriH1tF1RSGkv_ro3iSmnPZQ&s" alt="Petstore Logo" width="500"/>

## 📖 Introduction

This project is dedicated to testing the functionalities of the [Petstore API](https://petstore.swagger.io/).  
It serves as a practical exercise in API testing, focusing on creating, retrieving, updating, and deleting pet, store, and user data.

## ✨ Features

- **Pet Management**: Add, update, retrieve, and delete pet details.
- **Store Operations**: Place orders, retrieve orders, and manage store data.
- **User Management**: Create, update, retrieve, and delete user accounts.
- **Dynamic Variable Generation**: Generate dynamic variables in pre-request scripts to use across requests.

## 🛠️ Installation

Follow these steps to set up the project locally:

1. **Install Node.js**  
   Download and install Node.js from the [official website](https://nodejs.org/).

2. **Install Newman and HTML Extra Reporter**  
   Open your terminal and run:
   
   ```bash
   npm install -g newman
   npm install -g newman-reporter-htmlextra
   ```
3. **Clone this repository:**

   ```bash
   git clone https://github.com/AbdelrahmanFahmy0/Pet-Store-API-Project.git
   ```
   
4. **Navigate to the project directory:**
   
   ```bash
   cd Pet-Store-API-Project
   ```

5. **Import the Postman collection and environment into Postman:**
   - Open Postman.
   - Import the provided `Pet Store.postman_collection.json` and `Testing-Environment.postman_environment.json` files.

## 🚀 Usage

You can run the tests in two ways:

### Option 1: Run manually from Postman
- Open Postman.
- Choose the imported collection.
- Select the correct environment.
- Click **Run** to execute the test cases manually.

### Option 2: Run automatically using `run.bat`
- Locate the `run.bat` file inside the project directory.
- Double-click the `run.bat` file to start running the tests.
- This will automatically:
  - Run the Postman collection using Newman.
  - Generate an **HTML report** inside the `newman/` folder.


## 📄 Notes

- After the test execution, an HTML report will be available in the `newman` folder.
- If you face permission issues, run the terminal or `.bat` file as an administrator.
