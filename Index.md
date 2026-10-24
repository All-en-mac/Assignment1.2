1. Install Visual Studio Code
Download and install the latest stable version of VS Code for your operating system.

2. Install Node.js (LTS Version)
Go to the Node.js official website and download the LTS (Long Term Support) version. Run the installer and follow the setup prompts.

3. Install VS Code Extensions
Open VS Code, go to the Extensions view (Ctrl + Shift + X on Windows/Linux or Cmd + Shift + X on Mac), search for the following extensions, and click Install:

Live Server (by Ritwick Dey)

Prettier - Code formatter (by Prettier)

4. Create the Project Folder
Open your terminal (or Command Prompt / PowerShell) and create a new directory, or create it manually through your file manager:
mkdir web-development-practice
Open this newly created folder in VS Code (File > Open Folder...).

5. Create Core Files
Inside the web-development-practice folder, create three files:

index.html

style.css

script.js

(Tip: You can add some simple boilerplate text into index.html like <h1>Hello World</h1> so you have something to display).

6. Run via Live Server
Open index.html in VS Code.

Click the "Go Live" button in the bottom-right status bar of VS Code, or right-click inside the HTML file and select "Open with Live Server". This will automatically open your default browser to display the running page.

7. Verify Node.js and NPM Installation
Open your terminal or the integrated terminal in VS Code (Ctrl + ` ) and run:

Bash
node -v
npm -v
Note down or take a screenshot of the version numbers outputted in the terminal.
