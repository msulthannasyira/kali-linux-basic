# How to Install Chrome in Kali Linux

If you’re not familiar with the default browser that comes with Kali, you can download another browser instead. In this case, I want to download Chrome because it’s my favorite browser right now.

### 1. Download the Chrome .deb package

Visit the official Google Chrome download page:
[https://www.google.com/chrome/](https://www.google.com/chrome/?platform=linux)
Select the .deb package for Debian/Ubuntu-based systems and download it.

![image](https://github.com/user-attachments/assets/baddbf6b-cecd-48e3-b483-7592ec21aa43)

### 2. Open the terminal and navigate to the download location

For example, by default, the file is in the `Downloads` folder, run:

```bash
cd ~/Downloads
```

![image](https://github.com/user-attachments/assets/4a330851-5f5d-4aa2-9ca7-ae1e5cff8a86)

make sure you have the `google-chrome-stable_current_amd64.deb` files there

or you can just check it by the file explorer if it available or not

![image](https://github.com/user-attachments/assets/75604471-9c63-4da7-8eb4-a5174910d8c7)

### 3. Install the .deb package

Use the dpkg command to install the package

```bash
sudo dpkg -i google-chrome-stable_current_amd64.deb
```

Check if Chrome is installed by running
```bash
google-chrome --version
```

### 4. Launch Google Chrome

Start Chrome from the terminal with

```bash
google-chrome
```

Alternatively, find it in your desktop environment’s application menu.

![image](https://github.com/user-attachments/assets/8a640b44-4a66-4a91-8f10-831a5415b6af)

