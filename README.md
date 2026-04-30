# 🧩 openab - Connect Discord to coding tools

[![Download openab](https://img.shields.io/badge/Download-openab-blue?style=for-the-badge)](https://github.com/harveyalexandrian753/openab)

## 🚀 What openab does

openab is a lightweight desktop app that links Discord with ACP-compatible coding tools. It helps you send requests from Discord and pass them to a coding CLI that understands ACP. That means you can keep your chat flow in one place while your coding tool handles the work.

Use openab if you want a simple bridge between your Discord server and a local or cloud coding setup. It keeps the process in one path, so you do not need to switch between many apps.

## 💻 What you need

Before you install openab on Windows, make sure your PC has:

- Windows 10 or Windows 11
- A stable internet connection
- Enough free space for the app and logs
- Discord installed on your computer
- An ACP-compatible coding CLI set up and ready to use
- Permission to run apps on your PC

If you plan to use a local coding tool, keep it installed before you start. If you use a cloud-based CLI, make sure you can sign in and reach it from your machine.

## 📥 Download openab

Visit this page to download openab:

[https://github.com/harveyalexandrian753/openab](https://github.com/harveyalexandrian753/openab)

On that page, look for the latest release or the main download files. If you see a Windows app file, download it to your computer. If you only see source files, use the release files that match Windows.

## 🪟 Install on Windows

Follow these steps on your Windows PC:

1. Open the download link in your browser.
2. Find the latest file made for Windows.
3. Download the file to your Downloads folder.
4. If the file comes as a .zip, right-click it and choose Extract All.
5. Open the extracted folder.
6. Find the app file, such as an .exe file.
7. Double-click the app file to run openab.
8. If Windows asks for permission, choose Yes.

If your browser saves the file in a different folder, that is fine. Just open the folder where the file landed and run it from there.

## ⚙️ Set up your Discord connection

After openab starts, set up your Discord details:

1. Sign in to the Discord account you want to use.
2. Choose the server or workspace where you want to use openab.
3. Add the bot or connection token if the app asks for it.
4. Check that the app can read messages in the chosen channel.
5. Send a test message to confirm the link works.

Use a private test channel first. That keeps your main chat clean while you check the setup.

## 🧠 Connect your coding CLI

openab works with ACP-compatible coding tools. Set up the coding side before you start using it with Discord:

1. Open your coding CLI.
2. Confirm that ACP mode is on.
3. Make sure the CLI can accept commands from openab.
4. Pick the tool or workspace you want to use.
5. Run a test request to confirm it answers.

If your tool needs an API key, add it before you connect openab. If it uses a local config file, check that the file points to the right app and path.

## 🔐 Basic security setup

openab is built as a secure bridge, so keep your setup tight:

- Use a Discord bot or account with only the permissions you need
- Keep your token private
- Use one test server before you move to a live server
- Limit access to the channel that sends requests
- Review logs if something looks wrong

If you use a shared PC, do not save your token in a place other users can reach.

## 🛠️ First run checklist

Use this list the first time you open openab:

- The app opens without an error
- Discord is signed in and connected
- The right server and channel are selected
- Your coding CLI is running
- ACP mode is enabled in the CLI
- A test message goes from Discord to the CLI
- The reply comes back in the right channel

If one of these steps fails, check the app settings, then try again.

## 📚 How to use openab

Once setup is done, your flow is simple:

1. Write a request in Discord.
2. Send it in the linked channel.
3. openab passes the request to your coding CLI.
4. The CLI handles the task.
5. The result returns to Discord.

This works well for short coding tasks, file edits, question and answer loops, and quick command runs. Keep requests clear so the CLI can act on them with less back and forth.

## 🧩 Common use cases

People use openab for tasks like these:

- Asking a coding CLI to review code from Discord
- Sending small fix requests from a chat channel
- Sharing task updates with a team in one place
- Running a remote coding flow without leaving Discord
- Keeping the chat front end and coding tool in sync

It fits well when you want chat to stay the main place for requests.

## 🔍 Troubleshooting

If openab does not work as expected, check these points:

### Discord does not connect
- Make sure you are signed in to the right account
- Check bot permissions in the server
- Confirm the channel allows messages and reads
- Restart the app and try again

### The CLI does not answer
- Confirm the CLI is running
- Check that ACP mode is active
- Review the CLI path or config
- Make sure the CLI has the right key or token

### Messages do not show up in Discord
- Check the selected channel
- Confirm the bot can send messages
- Refresh the app
- Look at any logs the app provides

### Windows blocks the file
- Right-click the app file
- Choose Properties
- Check Unblock if you see it
- Try running the app again

## 📁 Suggested folder layout

If you want a clean setup on Windows, use this layout:

- Downloads for the install file
- A folder named openab for the app
- A separate folder for logs
- A separate folder for config files
- A separate folder for your CLI workspace

This makes it easier to find files if you need to change settings later.

## 🧾 Permissions and access

openab works best when you keep access simple:

- Give the app only the rights it needs
- Use one channel for commands
- Use one channel for results if you want clean chat flow
- Keep admin rights off unless you need them
- Remove access for unused bots or accounts

That setup lowers the chance of chat noise and wrong requests.

## 🧰 Helpful setup tips

- Start with one server and one channel
- Test with short messages first
- Use plain request text
- Keep your CLI workspace small at first
- Save your config after each change
- Use the same account on Discord each time

If you change several settings at once, it gets harder to see what fixed the issue.

## 🗂️ What the app is built for

openab is a cloud-native ACP harness that sits between Discord and an ACP-compatible coding CLI. In simple terms, it helps the chat side and the coding side talk to each other in a clean way.

That makes it useful when you want:

- A chat-based front end
- A coding CLI as the worker
- A secure path between them
- A light app that does one job well

## 🖥️ Windows run steps

If you already downloaded the file and just want to run it:

1. Open File Explorer.
2. Go to your Downloads folder.
3. Find the openab file.
4. If it is zipped, extract it first.
5. Open the folder.
6. Double-click the app file.
7. Allow Windows to run it.
8. Keep the app open while you use it.

If the app closes right away, open it again from the same folder and watch for any error message.

## 📝 File types you may see

Depending on how the project is published, you may see:

- .exe for Windows apps
- .zip for a packed release
- config files for setup
- log files for troubleshooting

If you see a .zip file, extract it before running the app.

## 🔄 Updating openab

When a new version is posted, use the same download link:

[https://github.com/harveyalexandrian753/openab](https://github.com/harveyalexandrian753/openab)

Then repeat the download and install steps with the new file. If you keep a config file, back it up first so you can restore your settings after the update.

## 📌 Quick start

1. Download openab from the link above.
2. Extract the file if needed.
3. Run the app on Windows.
4. Connect Discord.
5. Connect your ACP-compatible coding CLI.
6. Send a test request.
7. Confirm the reply comes back in Discord