[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15247205&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   1.Open a web browers
   2.Navigate to the visual studio code website/ download page.
   3.On the Visual Studio Code homepage you will see a download button. It should automatically detect that your're on windows and offer the windows download.click on download.
   4.run the installer by clicking on the setup file.
   5.Follow the setup wizard and after it has installed you can launch it

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   1.Installing Essential extensions such python,pylance,debugger for chrome etc
   2.contiguring settings such as editor font size,tab size,auto save and trim trailing to fit users needs
   3.by customizing Key bindings
   4. choosing themes and icons
   5.Configuring Version controls

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   1.Activity Bar- provides quick access to different views such as Explorer,Search,Source Control,Run and Debug,Extensions and more
   2.Side Bar-Displays the contents based on the selected activity.
   3.Editor-central area where you write and edit your code.supports multiple tabs for different files.allows split view for side by side editing.
   4.Status Bar-Located at the bottom of the window.It provides info about the open file and workspace.
   5.Panel-Hosts View such as terminal(for running shell commands),output(shows output from processes and extensions),Debug Console(displays debugging info),problems(lists errors and warnings in the code)
   6.Command Palette:provides a quick way to run commands without navigating menus.
   7.Editor Groups:Facilitates multitasking by displaying several files simultaneously.
   8.Minimap-Allows for quick navigation by clicking and dragging.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   -Command palette is feature that provides quick access to a wide range of commands and functions without needing to navigate through menus or remember complex keyboard shortcuts. it can be accessed by pressing Ctrl+Shift+P.Commands include view,file,Git,debug,Extensions.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   -Extensions enhance and expand the functionality of the Vs code.
   -users can bring u the extensions view by clicking on the extensions icon in the activity bar on the side of Vs code or view Extensions command(CTRL+Shift+X)

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   1.Using The menu:click on view in to Menu then select Terminal from the dropdown Menu.
   2.using keyboard shortcuts(CTRL+BACKTICK)
   3.Using the command palette:CTRL+SHIFT+P then type terminal to create a new Integrated Terminal and select it.
   adavantages include:seamless workflow Integration,multiple terminals can be operated at once,easy customization and configuration,has good environment consistency,has good command history and intelligence.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   >The File>add folder to workspace command brings up an open folder dialog to select the new folder.Once a root folder is added, the explorer will show the new folder as root in the file explorer. you right click on any of the root folders and use the context menu to add or remove folders/files.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   >To open the settings editor,navigate to File>Preferences>settings. Alternately, openthe settings editor from the command palette or open settings using keyboard shortcuts (CTRL+)


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   >SETTING UP STEPS INCLUDE:
   -After writing your python code you configure debugging by first opening the debug view
   -then create a debug configuration
   >STARTING DEBUGGING:
   -In the debug view,select the debug configuration you created(python:current file)
   -click the green play button or press F5 to start debugging.
   > key debugging features in Vs code include Breakpoints,Stepping,Variable Inspections,Call Stack,Debug connsole,Exceptions,Debugging extensions,Remote debugging,Integrated Terminal.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    >Inordr to integrate Git you have to download Git and link it with your Vs code.Once you authenticate with your GitHub acount in Vs Code,you'll be able to search through repositories by name,and select any repo to clone it.
    Process includes:
    1.Open Terminal.
    2.Navigate to the root directory of your project.
    3.Initialize the local directory as a Git repository. by default ,the inital branch is called main.
    4.Add the files in your new local repository
    5.Commit the filess that you've staged in your local repository

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

