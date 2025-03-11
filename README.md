# ChatGPT Mobile GitHub Integration 📱

🔗 [Prototype Link](https://www.figma.com/proto/cRGscAmsG8XQDdXQ2cviIq/CMPT363-MFP?node-id=1-280&t=6DPeMHl4LFd56fAk-1 )

## Introduction
This guide provides step-by-step instructions for setting up and using the ChatGPT mobile code editing prototype, specifically designed for seamless GitHub integration and mobile-friendly code editing and review. The main vertical task flow begins with the user connecting their ChatGPT and GitHub accounts and continue editing code based on their repository codebase, eventually pushing their newly edited changes.

### Contents

- [Horizontal Functionality](#key-horizontal-functions-implemented)
- [Vertical Functionality](#key-vertical-functions-implemented)
- [Step-by-Step Prototype Walkthrough](#getting-started)
- [Additional Features Screenshots](#additional-features)

---

### Key Horizontal Functions implemented:
- Visibility of System status popup
- ChatGPT login options for login with Google, Microsoft, Apple, or Phone
- Chat History and Menu sidebar
- ChatGPT help information popup
- Create a new account page
- Viewing all repositories
- Copying code snippet
- Creating a new chat
- Code edit history
- Undo / Redo code changes
- User error prevention

### Key **Vertical** Functions implemented:
- ChatGPT login user task flow
- GitHub Login integration
- Importing a repository for chat context
- Prompting for code edits in a specific file (ex. File1.py)
- Viewing entire code file
- Accept / Decline Changes
- Pushing new changes to the repository

---

# Getting Started

### Step 1: Login Process

1. Open the **ChatGPT Figma Prototype** [Prototype Link](https://www.figma.com/proto/cRGscAmsG8XQDdXQ2cviIq/CMPT363-MFP?node-id=1-280&t=6DPeMHl4LFd56fAk-1 )

2. Tap the **top-right login button** to enter the login interface

<p align="center">
  <img src="https://github.com/user-attachments/assets/dd638e62-ddfe-44f1-8a1f-27780e3a9457" width="200" />
</p>

4. Click the green **Continue** button, or choose your preferred login method by selecting one of the following options:
   - **Continue with Google**
   - **Continue with Microsoft Account**
   - **Continue with Apple**
   - **Continue with phone**
   - **Sign up and continue with ChatGPT**

<p align="center">
  <img src="https://github.com/user-attachments/assets/60d220e9-6fc5-4e40-b3bb-2180fadf4315" width="200" />
</p>

---

### Step 2: Connect GitHub Account

1. After logging in, tap the **Menu** button in the **top-left corner** to open the menu sidebar

<p align="center">
  <img src="https://github.com/user-attachments/assets/d8b4a55a-12d6-4c6c-91ee-63817ca618be" width="200" />
</p>

3. Click **Integrations** 

<p align="center">
  <img src="https://github.com/user-attachments/assets/f975ccd2-2279-44c0-abf7-65964c188d28" width="200" />
</p>
   
5. Tap the **GitHub** button to access the GitHub login interface

<p align="center">
  <img src="https://github.com/user-attachments/assets/11b70000-15ba-4a5c-a431-3de19ce42628" width="200" />
</p>

7. GitHub credentials are prefilled, click the **Sign In** button

<p align="center">
  <img src="https://github.com/user-attachments/assets/b045fafd-d705-45a6-a854-57604b994a3a" width="200" />
</p>

8. Navigate back using the back button at the top left corner of the screen

<p align="center">
  <img src="https://github.com/user-attachments/assets/b291221f-4f3e-47d9-883b-9433f933a1d3" width="200" />
</p>


---

### Step 3: Select GitHub Repository

1. After linking GitHub, click on **Import Repository** in the chat screen

<p align="center">
  <img src="https://github.com/user-attachments/assets/ce9d8121-2fdc-4155-8a65-e4372f629dfc" width="200" />
</p>

3. Select the first repository from the displayed list, **Repository 1**

<p align="center">
  <img src="https://github.com/user-attachments/assets/4ff9789c-5175-483b-96f6-3fe8b6f987db" width="200" />
</p>

---

### Step 4: Review and Edit Code

1. After selecting a repository, a **sample prompt** is provided in the prototype: tap the **Send button** in the bottom-right

<p align="center">
  <img src="https://github.com/user-attachments/assets/eaca4c91-d7b3-4b72-a65a-408031b0e7e7" width="200" />
</p>

4. Tap **Show Full Code** to open the code editing page

<p align="center">
  <img src="https://github.com/user-attachments/assets/967771e7-e660-4d75-988e-8692944f8b5a" width="200" />
</p>

6. Click **Accept Changes** above the code suggestions highlighted in blue

<p align="center">
  <img src="https://github.com/user-attachments/assets/f040cff2-c654-420d-b992-f7f9ac59ad11" width="200" />
</p>


---

### Step 5: Push Changes to GitHub

1. Click the **top-right upload icon**

<p align="center">
  <img src="https://github.com/user-attachments/assets/a318d52f-f3c6-4c1b-becf-7b1b523e6d7d" width="200" />
</p>

3. Select **Push to Main** from the dropdown menu

<p align="center">
  <img src="https://github.com/user-attachments/assets/b0447861-5401-4fc2-beea-0d2fa27328b1" width="200" />
</p>
   
6. After reviewing changes, tap the **Commit Changes** button at the bottom of the page

<p align="center">
  <img src="https://github.com/user-attachments/assets/b17584a8-8957-4d99-ac56-e24d44f85bf0" width="200" />
</p>

8. Click **Commit** in the popup dialog

<p align="center">
  <img src="https://github.com/user-attachments/assets/f1c62376-2917-4ca2-8b72-bc6b2aa05bcd" width="200" />
</p>

10. Your changes will be committed to your repository. Tap **Back to Chat** to return to the chat screen and complete the workflow

<p align="center">
  <img src="https://github.com/user-attachments/assets/4830429a-3243-490f-ba76-b5381850cc22" width="200" />
</p>

Thats it! You've completed the vertical functionality of our prototype.

---

## Additional Features

### View Edit History
- Tap the **History** button at the top toolbar section at any time to review past changes

<p align="center">
  <img src="https://github.com/user-attachments/assets/d0886344-adff-4ec8-9d51-129984bd087c" width="200" />
  <img src="https://github.com/user-attachments/assets/4cf9722d-8b1b-4b4e-b9ba-7ab5a52227d0" width="200" />
</p>

### **Mistake Recovery**
- Users can **undo an action** to revert accepted changes in the code editor
- The prototype tracks **changes made**, prompting users to push their updates in the chat screen

<p align="center">
  <img src="https://github.com/user-attachments/assets/d0886344-adff-4ec8-9d51-129984bd087c" width="200" />
  <img src="https://github.com/user-attachments/assets/5a0e5d5c-5bb9-4b9e-99fe-2d2d7a7003d3" width="200" />
</p>


### **Account and Session Management**
- Users can review the **Terms and Privacy Policy** anytime within the login session for **clarity and security**
- Users can view their chat history at any time within the sidebar window

<p align="center">
  <img src="https://github.com/user-attachments/assets/08aa46ba-7ef2-487e-8d07-060e1f3c97b3" width="400" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1ab59d27-c442-420e-bc0c-a834dd2e31c8" width="200" />
  <img src="https://github.com/user-attachments/assets/a55258a9-dab6-4c33-a583-4be2a01da9df" width="200" />
</p>

### Mobile Keyboard Shortcuts
- Code editing is improved with common keyboard buttons easily accessible

<p align="center">
  <img src="https://github.com/user-attachments/assets/d9edd1eb-b1b1-4e13-9ea3-62aaa78e1255" width="200" />
</p>


