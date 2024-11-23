# Full Upgrade & Update

When you first install Kali Linux, it’s important to perform an update and upgrade to ensure that your system is running the latest security patches, applications, and other updates. This is a common step people take when setting up any Linux OS, and it’s especially important in Kali Linux to stay up-to-date with the latest tools and security fixes.

To do this, you can open a terminal and run the necessary commands. This will update your package list and upgrade the installed software, making sure you have the newest versions of everything directly from the official Kali repositories.

Update your package list: This ensures your system knows about the latest available updates for all installed packages.

## 1. Update your package list

This ensures your system knows about the latest available updates for all installed packages.

```cmd
sudo apt update
```

![image](https://github.com/user-attachments/assets/9f60177d-a8fa-47a4-bed4-bf44cc72c381)

## 2. Upgrade your installed packages

This upgrades all the packages that are installed to the latest versions available.

```cmd
sudo apt full-upgrade -y
```

![image](https://github.com/user-attachments/assets/1fc314d3-0961-4524-9616-85b7f93bce2c)

![image](https://github.com/user-attachments/assets/c28ad848-8b06-4f4d-ad31-1d01761b5f0d)

Running these commands is a key step right after you first boot up Kali Linux, ensuring you have the latest security patches, applications, and tools that Kali offers. You can always check for new updates by running these commands regularly to keep your system in top shape.

