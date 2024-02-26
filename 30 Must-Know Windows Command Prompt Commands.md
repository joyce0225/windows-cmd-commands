# 🛠️ 30 Must-Know Windows Command Prompt Commands

## 🚀 Starting and Customizing CMD
1. **Open CMD as Administrator by Default**: Modify CMD shortcut properties to always run as administrator. 🛡️
2. **`copy /b`**: Hides a zip file inside an image. 🖼️🔒
3. **`cipher /e`**: Encrypts files in a folder. 🔐
4. **`attrib +h +s +r`**: Hides a folder. 🙈
5. **`attrib -h -s -r`**: Reveals a hidden folder. 👀
6. **`netsh wlan show profile`**: Shows all Wi-Fi networks connected to. 📶
7. **`netsh wlan show profile [network] key=clear`**: Reveals Wi-Fi password in plain text. 🔑
8. **Extracting Saved Wi-Fi Passwords on Windows (rmb to change directory to desktop first**:
   This command is used in Windows Command Prompt to extract and save the Wi-Fi profiles and their corresponding passwords that are stored on a computer.
   ```cmd
   for /f "skip=9 tokens=1,2 delims=:" %i in ('netsh wlan show profiles') do @if "%j" NEQ "" (echo SSID: %j & netsh wlan show profiles %j key=clear | findstr "Key Content") >> wifi-password.txt

9. **Batch File for Wi-Fi Passwords**: Create a .bat file to easily display all stored Wi-Fi passwords. 📝
10. **`systeminfo`**: Displays detailed system information. 💻
11. **`scp` (Secure Copy)**: Copies files to a remote server securely. 🌐

## 🗂️ File and Folder Management
11. **Open CMD from Explorer**: Type CMD in the address bar of any folder. 📁
12. **Open Explorer from CMD**: Type `explorer .` in CMD. 🖥️
13. **Map Folder as Drive**: Use `subst` command to assign a drive letter to a folder. 💾
14. **Remove Mapped Drive**: Use `subst /d` to remove a mapped drive. ❌

## 🎨 Enhancing CMD Appearance
15. **`color`**: Changes CMD text and background color. 🎨
16. **`prompt`**: Customizes the command prompt text. ✒️
17. **`title`**: Sets a custom title for the CMD window. 🏷️

## 🌐 Networking and Online Tools
18. **`curl`**: Versatile command for web interactions, like checking weather or unshortening URLs. ☁️
19. **Public IP Address**: Use Curl to find your public IP address. 🌍
20. **Create QR Codes**: Generate QR codes with Curl. 📱
21. **YouTube and Twitter Updates**: Use Curl to get the latest video from a YouTube channel or tweet from Twitter. 📺🐦
22. **`telnet`**: Access the Telnet client for various online fun. 🕹️

## ⌨️ CMD Keyboard Shortcuts
23. **`F1` to `F9` Keys**: Various shortcuts for repeating commands and navigating CMD history. ⏪
24. **`doskey /history`**: Lists all previously entered commands. 📜

## 📚 Learning and Assistance
25. **`help`**: Provides a list of all available commands. ❓
26. **Command Specific Help**: Use `[command] /?` for detailed help on a specific command. 📘

## ⚡ Advanced CMD Tips
27. **Switch to Windows Terminal**: Embrace the new Windows Terminal for more features. 🆕
28. **Drag and Drop in Terminal**: Drag files directly into the terminal for easier path insertion. 🖱️
29. **Open Terminal from Explorer**: Shift + Right Click to open a terminal window directly. 🖥️
30. **Use PowerShell**: PowerShell offers more power and flexibility than CMD. 💪

These commands and tips enhance your CMD experience, making it more efficient and powerful for various tasks. 💻🌟
