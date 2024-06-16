![image](https://github.com/Powerlearnproject/se-assignment-5-Gathu88/assets/172362126/5488b9ef-71c2-406a-bb4a-321dbc75c86f)[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283987&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - Visual studio code is a code editor that optimizes code writing and debugging.
     - Requsite for installing Visual Studio Code: Window 10 or 11, the higher the version the better. Internet to support downloading Visual Studio Code.
     - Steps to download and install Visual Studion Code on Windows 11 OS.
        - Open your browser and type in Visual Studio code or https://code.visual studio.com and click on the download Visual Studio for the operating system that you have. Since I am using windows 10, I will choose windows OS. Follow the on-screen instructions to download the installer.
        - Run the Installer - Run the downloaded installer (VSCodeUserSetup-{version}.exe) and then choose the Visual Studio general setting during the installation.
        - By default the VS Code is isntalled under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code.
        - In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."(plp 2024)
- When the download process is complete, the Visual Studio Code will appear in the download folder.
- Click on the insatller icon and the installation process will beginn
- After the Installer opens, a dialogue box will appear asking you to accept terms and conditions. Read through the terms and conditions and accpet the agreement and clickk the next button. Installation of VS code will not continue unless you accept the terms and consitions
- Choose the location data for running VS Code. It will ask you to browse the location- click on the C drive and then click next.
- The installer will ask you to begin th installation setup, click next to continue with the installation. The process will take a minute or more depending onn the speed of your computer/laptop.
- After VS code installation is finished, a window with the following will appear "completing the visual studion code setup wizard will appear. Click on the box writtenn Launch Visual Studio Code and proceed to click on the on the finish button.
- The VS Code window shoudl will open successfully. Inorder to start codding, choose a language to beggin your prorammig journey.  
- 

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   - Extensions lets a programmer to add languages, debuggers and tools to the VS Code intallation to aid in development workflow. It lets the programmer to explore VS Code's extensibility model and lets the code author access the VS Code UI and contrubute functionality through the same APIs used by VS Code (https://code.visualstudio.com).
   - Browse and install extension from within the VS Code. Bring up  the extensions view by clicking on the extention Icon in the Activity Bar on th side of the VS code or the View - Extension command. This will dispaly a list of the most popular VS Code extensions on the VS market place. Examples include python, c/c++
   - Mamaging extensions- one can install, disable, update, and uninstall extensions through the Extensions view, the Command Palette, which have extensions prefix or command line switches.
   - List of installed extensions - By default, the Extensions view will show the extensions you currently have installed, and all extensions that are recommended for you depending on what you are working on. In order to view the list of extesions in VS Code use the followings kesys (Ctrl+Shift+P) or in the More Actions (...) dropdown menu > Views > Installed, to clear any text in the search box and show the list of all installed extensions, which includes those that have been disabled.
   - To untinsatll an extention- select the Manage gear button at the right of an extension entry and then choose Uninstall from the dropdown menu. This will uninstall the extension and prompt you to restart the extension host (Restart Extensions).
   - To Disable an extension- f you don't want to permanently remove an extension, you can instead temporarily disable the extension by clicking the gear button at the right of an extension entry. You can disable an extension globally or just for your current Workspace. You will be prompted to restart the extension host (Restart Extensions) after you disable an extension. If you want to quickly disable all installed extensions, there is a Disable All Installed Extensions command in the Command Palette and More Actions (...) dropdown menu. 
Extensions remain disabled for all VS Code sessions until you re-enable them.
- Enabling extension-if you have disabled an extension (it will be in the Disabled section of the list and marked Disabled), you can re-enable it with the Enable or Enable (Workspace) commands in the dropdown menu.
- Auto updating extensionn -VS Code checks for extension updates and installs them automatically. After an update, you will be prompted to restart the extension host (Restart Extensions). If you'd rather update your extensions manually, you can disable auto-update with the Disable Auto Updating Extensions command that sets the extensions.autoUpdate setting to false. If you don't want VS Code to even check for updates, you can set the extensions.autoCheckUpdates setting to false.
- Recoomended extension-You can see a list of recommended extensions using Show Recommended Extensions, which sets the @recommended filter. Extension recommendations can either be:
        -Workspace Recommendations - Recommended by other users of your current workspace.
        -Other Recommendations - Recommended based on recently opened files.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   - Visual Studio Code includes a full featured integrated terminal that starts at the root of your workspace. It provides integration with the editor to support features like links and error detection. The integrated terminal can run commands such as mkdir and git just like a standalone terminal.
   - You can open a terminal as follows:
-From the menu, use the Terminal > New Terminal or View > Terminal menu commands.
-From the Command Palette (Ctrl+Shift+P), use the View: Toggle Terminal command.
-In the Explorer, you can use the Open in Integrated Terminal context menu command to open a new terminal from a folder.
-To toggle the terminal panel, use the Ctrl+` keyboard shortcut.
-To create a new terminal, use the Ctrl+Shift+` keyboard shortcut.
    - Advantage of using the intergrated terminal compared to an external terminal - Internal terminal provides integration with the editor to support features like links and error detection. The integrated terminal can run commands such as mkdir and git just like a standalone terminal.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    - -Git bash is an application that provides Git command line experience on the Operating System. It is a command-line shell for enabling git with the command line in the system. VSCode is a Text editor that provides support for development operations and version control systems. It provides tools for a user to build hassle-free codes. One should have an adequate understanding of these as they serve as prerequisites.
    - Initializing a respiratory , Making commits, and pushing changes to GitHub
        -To push your local changes to the remote repository, in the repository bar, click Push origin.
        - If there are commits on the remote branch that you don't have on your local branch, GitHub Desktop prompts you to fetch new commits from the remote. In the "New Commits on 
        Remote" window, click Fetch.
        - Optionally, click Preview Pull Request to open a preview dialog where you can review your changes and begin to create a pull request. For more information, see "Creating an 
        issue or pull request from GitHub Desktop."

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

