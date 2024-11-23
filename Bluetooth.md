# Enable Bluetooth on Kali Linux

If you have earphones but don't know how to connect them to Bluetooth on Kali Linux, here's the tutorial

## 1. Install Bluetooth Tools

Ensure your system has the necessary Bluetooth packages:

```cmd
sudo apt install bluetooth bluez bluez-tools rfkill
```

## 2. Check for Bluetooth Services

Start and enable the Bluetooth service

```cmd
sudo systemctl start bluetooth
sudo systemctl enable bluetooth
```

make sure the service already running

```cmd
systemctl status bluetooth
```

## 3. connet your device

search `bluetooth manager` on main menu

![image](https://github.com/user-attachments/assets/9f60c874-7650-4b12-a6ec-af4c36d67586)

simply connect it

![image](https://github.com/user-attachments/assets/af3c29f9-885a-4419-8b4b-c01c8a0c89c3)


