name: MICHAEL GONA KATANA   email: mickeygkatana@gmail.com
SOFTWARE ENGINEEERING ASSINGMENT 5- SETTING VS CODE.

QUIZ 1. Downloading and installing Visual Studio Code on windows 11
    (a) Open your browser window and type the url: https://code.visualstudio.com/download to visit the official visual studio site.
    (b) Click on the download for windows icon to download the installation package.
    (c) Run the installer after the download is complete to initiate the installation one.
    (d) Accept the license agreement and use the default location folder
            C:\Users\PC\AppData\Local\Programs\Microsoft VS Code\bin\code
    (e) Select addition task,  creating a desktop icon, add to Path.
# image on downloading and installing vs code:
![downloading vs code](<images/vs_code_download.png>)



QUIZ 2. First-time Setup:
    (a) Adjust appearence and themes - Go to File > Preferences > Color Theme to choose a theme.
    (b) Edito Settings: Adjust settings such as font size and line height via File > Preferences > Settings or Ctrl+,
# images below:
![settings](<images/settings.png>)



QUIZ 3. Main components of the VS Code user interface.
    (a) Activity Bar: The vertical bar on the far left. It provides access to different views like Explorer, Search, Source Control, and Extensions.
    (b) Side Bar: The container for views and their content. It changes based on the selection in the Activity Bar (e.g., file explorer or source control).
    (c) Editor Group: The main area where files are displayed and edited. You can have multiple editor groups side by side.
    (d) Status Bar: Located at the bottom. It provides information about the current project, such as branch, file encoding, line/column numbers, and more.



QUIZ 4. Command Palette:
    This is a section in visual studio code where you can type, search and execute commands. The command palette can be accessed by: Ctrl+Shift+P (or F1).
    Common task that can be perfomed- Opening files: Type Open File.
# Image of command palette.
![command pallete image](<images/palette.png>)



QUIZ 5. Extensions in VS Code:
Extensions add functionality and support for different languages, tools, and frameworks.
To access and install extensions click on, file > preferences > extensions or CTRL+Shift+X or the extension icon on the left side bar.
From here, we can install, uninstall and view avaialble extension in vs code.
    Essential extensions for web development:
    HTML CSS Support: Provides IntelliSense for HTML and CSS.
    JavaScript (ES6) code snippets: Adds useful code snippets for JavaScript development.
    VS Code Icons: Adds file icons for better visual identification.
# image on extension:
![extension page](<images/extensions.png>)



QUIZ 6. Integrated Terminal:
To open and use the intergrated terminal, go to: view > Terminal or click: CTRL+`
After starting it, you can then type the commands you wish to run.
 ADVANTAGES:
As it is intergrated within vs code, it helps to remain on vs without switching to an external command line.
You can configure shell terminal theme and prefeences.
# terminal image example:
![terminal](<images/terminal.png>)



QUIZ 7. File and Folder Management:
To create new files/folders: Right-click in the Explorer view and select "New File" or "New Folder".
Opening files/folders: Use the Explorer view or File > Open Folder to open a folder.
Managing files or folders: Use the Explorer view for visual navigation, Ctrl+P to quickly open files by name.



QUIZ 8. Settings and Preferences:
To access settings, user can: Go to File > Preferences > Settings or press Ctrl+,.
    to perform some customization, i.e.,
Changing theme: Search for Color Theme and select your preferred theme.
Changing font size: Search for Editor: Font Size and adjust the value.
Changing keybindings: Go to File > Preferences > Keyboard Shortcuts or press Ctrl+K, Ctrl+S



QUIZ 9. Debugging in VS Code:
Setting up and starting debugging:
    1: Open your project and set breakpoints by clicking in the gutter next to the line numbers.
    2: Go to the Run and Debug view by clicking the Run icon in the Activity Bar.
    3: Click the play button or press F5 to start debugging.
        Key debugging features:
    Watch: Monitor variables and expressions.
    Call Stack: View the call stack to understand the execution flow.
    Variables: Inspect the current state of variables.


QUIZ 10. Using Source Control:
    Integrating Git with VS Code:
To initialize a repository, Open your project folder in VS Code, go to the Source Control view, and click "Initialize Repository".
You can stage changes by clicking the "+" icon next to files, enter a commit message, and click the checkmark to commit.
    Pushing changes to GitHub:
    (a) Ensure you have a remote repository set up on GitHub.
    (b) Use Ctrl+Shift+P to open the Command Palette and type Git: Add Remote.
    (c) Enter the GitHub repository URL.
    (d) Use the Source Control view to push changes by clicking the "…" icon and selecting Push.