# Screenshot and screenrecorder

Since the default screenshot (clipboard) and screen recorder applications are not very good for me, I decided to look for alternatives. I found two great options: Flameshot and Kazam. Here are the steps to use them!

## Flameshot

"This is actually 'post-download' applications in Linux that can work magic with screenshots, similar to what Windows does!"

### 1. Install Flameshot

Flameshot is available in the default Kali Linux repositories. Install it using the following command

```bash
sudo apt install flameshot -y
```

### 2. Verify Installation

After installation, you can check if Flameshot is installed by running

```bash
flameshot --version
```

### 3. Launch Flameshot

You can launch Flameshot in the following ways:

From the Terminal type `flameshot` and press Enter.

or

From the Applications Menu: Look for "Flameshot" in the system menu.

![image](https://github.com/user-attachments/assets/d8a3ab64-54d1-46da-8c98-805c4c178667)

take screenshot of flameshot with flameshot

fyi all the screenshot in this repo were taken with flameshot :)

## Kazam

this application just work similar with popular screenrecorder were, like xbox recorder, bandicam, camtasia, etc

### 1. Install Kazam

Kazam may not be in the default Kali Linux repositories, but it is available in the Ubuntu repositories, which Kali Linux can access. Install it with

```bash
sudo apt install kazam -y
```

### 2. Verify Installation
   
After installation, check if Kazam is installed by running:

```bash
kazam --version
```

### 3. Launch Kazam

From the Terminal type kazam and press Enter
or 
From the Applications Menu: Search for `Kazam` in your desktop environment's app menu.

Warning: Kazam default video format is AVi with the most high quality and no compression, so I recommended you to change the video format in `file` -> `preferences` -> `screencast` -> `recordwith`

![image](https://github.com/user-attachments/assets/5fbc274d-f121-4f4f-ba23-12befb037445)
kazam main menu

![image](https://github.com/user-attachments/assets/9372a538-f0a4-4b94-af4e-fa261caae589)
kazam video format











