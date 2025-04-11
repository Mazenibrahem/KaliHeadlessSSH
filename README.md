# Kali Headless SSH Launcher

This project includes two simple `.bat` scripts to help you start your Kali Linux VirtualBox VM in headless mode and connect to it via SSH directly from your Windows system.

## Files

- `start_kali.bat`: Starts the Kali VM in headless mode using VBoxHeadless.
- `connect_ssh.bat`: Connects to the running Kali machine via SSH.

## Usage

1. Make sure the VM name matches exactly:
   - `"kali-linux-2022.4-virtualbox-amd64"` (You can change it in the script if your VM has a different name).

2. Make sure SSH is enabled and configured on your Kali VM.

3. Update the IP in `connect_ssh.bat` if needed:
   ```bat
   ssh kali@YOUR_KALI_IP
   ```

4. Double-click the `.bat` files to run.

---

### Optional:
You can set up SSH keys to avoid entering the password every time.

Enjoy fast Kali access! 🐍💻
