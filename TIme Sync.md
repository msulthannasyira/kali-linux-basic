# Time Synchronization

When you first install Kali Linux, the system might sync its time with the CMOS clock from your previous or another operating system. However, for some reason, this synchronization might stop working after the initial setup. If you try to adjust the time manually, it can cause issues, such as websites not functioning correctly. To resolve this, you need to enable automatic time synchronization in Kali Linux, similar to how Windows syncs with a time server. Here are the steps to set it up:

### 1. Install the NTPsec Package

The NTPsec library is used to synchronize the system time automatically. Install it with the following command

```bash
sudo apt install ntpsec
```

### 2. Start the NTPsec Service

Once the library is installed, start the NTPsec service to enable time synchronization

```bash
sudo systemctl start ntpsec
```

### 3. Enable NTPsec to Start on Boot

To ensure the NTPsec service runs automatically at boot, enable it using this command

```bash
sudo systemctl enable ntpsec.service
```

### 4. check the status

You can check the status of the NTPsec service with the following command

```bash
sudo systemctl status ntpsec.service
```

If the system time does not update immediately, wait a moment for the synchronization to take effect. This delay is normal.


