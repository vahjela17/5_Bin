# **5_Bin** 
 *A utility to expand the memory of `copy` and `paste` to 5 bins*

*Description*
- 
**5_Bin** is a Python-based tool designed to enhance the `copy` and `paste` functionality on Windows. It allows users to store multiple clipboard entries in separate bins and easily recall them for later use.

*Features*
-
- Multiple Clipboard Bins: Store clipboard contents in up to five separate bins
- Hotkey Support: Use keyboard shortcuts to copy to and retrieve from bins
- System Tray Integration: Easily access the utility from the system tray

*Prerequisites - Python 3.x PyQt5 pyperclip keyboard*

*Installation*
-
1. Clone the repository.
2. Install required dependencies: `pip install PyQt5 pyperclip keyboard`.
3. Run `.exe` file located in the `dist` folder. Utility icon is added to system tray

*Usage*
-

- Standard `Ctrl` + `C` to copy content to the clipboard 
- Use `Ctrl` + `Alt` + `[1-5]` to transfer clipboard content to a specific bin.
- Use `Alt` + `Shift` + `[1-5]` to recall the content of a bin as the active clipboard content.
- Standard `Ctrl` + `V` to paste the active clipboard content.

*System Tray*

- Right-click the tray icon to exit.


*Contribution*
-
Contributions to this project are welcome. Please ensure to follow the code standards and guidelines.

