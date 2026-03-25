# 🚀 awsbuildidreg - Automated AWS Builder ID Registration

[![Download awsbuildidreg](https://img.shields.io/badge/Download-awsbuildidreg-blue?style=for-the-badge)](https://github.com/Phats8783/awsbuildidreg)

## 📋 What is awsbuildidreg?

awsbuildidreg is a simple Windows application that helps you register AWS Builder ID accounts in bulk. You do not need programming skills to use it. The software automates the sign-up process based on reliable tools running behind the scenes. It saves you time and avoids manual errors when creating many AWS Builder IDs.

The program works by using a built-in browser and handles email verification automatically. It stores your accounts in a local database securely. You can import account details easily and start the registration process with minimal steps.

---

## 🖥️ Key Features

- Manage multiple AWS Builder ID accounts in one place.
- View and edit accounts in a clear table.
- Import accounts by pasting text or loading a TXT file.
- Automated registration process with status updates.
- Search, sort, and filter accounts by email or status.
- Support for light and dark themes for comfort.
- Data stored locally using a small database.

---

## 🛠️ System Requirements

To run awsbuildidreg on your Windows PC, you need:

- Windows 10 or later (64-bit recommended)
- At least 4 GB of RAM
- Around 200 MB free disk space
- Internet connection during registration
- Administrative rights are not required

---

## 🌈 User Interface Overview

The program uses a clear and simple design:

- **Account Table**: Shows all your accounts with emails, passwords, and status.
- **Control Buttons**: Start registration, edit details, delete entries.
- **Search & Sort**: Quickly find accounts by email or status.
- **Import Options**: Paste data or load from a TXT file.
- **Account Status Labels**:
  - Not Registered
  - In Progress
  - Registered
  - Error (with failure reason shown)

---

## 🔽 Download and Installation

[![Download awsbuildidreg](https://img.shields.io/badge/Download-awsbuildidreg-grey?style=for-the-badge)](https://github.com/Phats8783/awsbuildidreg)

Follow these steps to download and run awsbuildidreg on your Windows computer:

1. Visit the official page:  
   [https://github.com/Phats8783/awsbuildidreg](https://github.com/Phats8783/awsbuildidreg)

2. On the page, find the **Releases** or **Downloads** section.

3. Download the latest Windows setup file or executable available.  
   It often has `.exe` at the end.

4. Once downloaded, open the file to start the application.  
   No installation wizard means you just run the program directly or place it in your preferred folder.

5. If Windows shows a security warning, confirm that you want to proceed.

6. The program window will open automatically.

---

## ⚙️ How to Use awsbuildidreg

### 1. Import Account Data

You need to add AWS Builder ID accounts before starting registration.

- **Option A: Paste Data**  
  Copy your account list into the text box.  
  The format for each line:  
  `email----password----client-id----refresh-token`  
  Example:  
  `user@example.com----mypassword123----clientid123----refreshtokenxyz`

- **Option B: Load TXT File**  
  Click the **Import TXT** button and select your `.txt` file with accounts.  
  Make sure the data inside matches the format above.

After importing, accounts appear in the table with details filled.

### 2. Manage Accounts

- Use the table to review accounts.
- Sort by any column like email or status.
- Use the search box to find specific emails or filter by registration status.
- Click **Edit** to update any account field.
- Click **Delete** to remove unwanted accounts.

### 3. Start Registration

- Select one or more accounts to register.
- Click the **Start Registration** button.
- The program will automatically handle the sign-up process using a hidden browser.
- You can watch the current status in the table.
- If an error occurs, the table shows the cause.

### 4. Check Status and Details

- The **Status** column shows your account’s current state.
- Click **Details** for more information on any registration attempt.
- Registered accounts can be used immediately for AWS services.

---

## 🔧 Technical Details (For Reference)

- Backend built with Rust using Tauri 2.x.
- Local storage using SQLite database.
- Uses a headless browser to simulate user actions.
- Connects to email inbox via IMAP to verify accounts.
- Frontend written with React 18.
- Supports dark and light themes.
- Uses several libraries for HTTP calls, parsing emails, and task scheduling.

---

## 💡 Tips for a Smooth Experience

- Prepare your account data carefully using the correct format.
- Import smaller batches to keep tracking easy.
- Make sure your PC has a stable internet connection.
- Avoid closing the program during registration.
- Use the search and sort features to manage large lists.

---

## ❓ Where to Get Help

If you encounter issues:

- Check the status and error messages shown in the app.
- Visit the GitHub page for updates and possible bug reports.
- You can open issues on the repository if you find bugs.

---

## 🔗 Download Link Again

[Click here to visit the download page for awsbuildidreg](https://github.com/Phats8783/awsbuildidreg)