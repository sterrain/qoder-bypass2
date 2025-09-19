# QoderBypass

A tool to bypass Qoder limitations by spoofing machine ID and managing the application.

⭐ **If this tool helps you, please consider starring this repository on GitHub to support the project!** ⭐

## Changelog

- [Qoder Bypass 1.22 Changelog](https://github.com/ProTechPh/qoder-bypass/commits/Qoder-Bypass-1.22)
- [Qoder Bypass 1.23 Changelog](https://github.com/ProTechPh/qoder-bypass/commits/Qoder-Bypass-1.23)
- [Qoder Bypass 0.2.1 Changelog](https://github.com/ProTechPh/qoder-bypass/compare/Qoder-Bypass-1.22...Qoder-Bypass-0.2.1)
- [Qoder Bypass 0.2.2 Changelog](https://github.com/ProTechPh/qoder-bypass/compare/Qoder-Bypass-0.2.1...Qoder-Bypass-0.2.2)

## Requirements

- Windows (no macOS support)
- Admin access on your PC
- Qoder application installed

## How to Use

### Step 1: Download and Setup
1. Download the QoderBypass.exe from this repository
2. Make sure Qoder is installed on your system
3. **Important:** Turn off automatic updates in Qoder settings to prevent the bypass from breaking when new versions are released

### Step 2: Close Qoder
Close Qoder before launching QoderBypass (the script should do this automatically anyway)

### Step 3: Run QoderBypass
1. Open PowerShell (or CMD) as Administrator
2. Navigate to the folder containing QoderBypass.exe
3. Run the executable:
   ```powershell
   .\QoderBypass.exe
   ```
4. You'll get a UAC prompt (if UAC is enabled), press "Yes"

### Step 4: Sign Out and Create New Account
1. Sign out from your current Qoder account (changing machine ID does this automatically)
2. Create a new account (old accounts won't work)
3. Boom! Should work now

## Usage Notes

⚠️ **Important:**
- Opening this script closes your old Qoder instance
- Closing this script also closes Qoder
- The bypass needs to be running at all times (because of memory operations)
- When you exit the app and open it again, you get signed out (should be fine when switching folders in Qoder)

## Hotkeys

Default hotkeys (can be configured in the source):
- **Page Down**: Generate new machine ID (regen)
- **End**: Toggle freeze

## Creating New Accounts

If you want to make a new account (for example, if you used 2k credits fully):

1. Sign out if you haven't already
2. Spoof by pressing "Page Down" 
3. Press login in the GUI and create a new account (you can use tempmail)

## Troubleshooting

- Make sure you have admin privileges
- Ensure Qoder is properly closed before running QoderBypass
- If issues persist, try running as Administrator
- Remember that old accounts won't work after spoofing - you need to create new ones

## Frequently Asked Questions (FAQ)

### 1. Do you need to spoof VS Code so this thing works?
**Answer:** No, you don't need to spoof VS Code. Use only QoderBypass tool to spoof Qoder.

### 2. How to check if spoofing is working?
**Answer:** Check the console output and logs when running the tool. The application will show status messages indicating successful machine ID changes.

### 3. Spoofing does not work!!!! (I got banned)
**Answer:** First check:
- Did you have QoderBypass running when you registered the account?
- Did you use an old account or register a new account to use Qoder?

If you used an old account, it will definitely not work. Same with banned accounts - this tool will **NOT** unban already banned accounts.

### 4. Which versions are officially supported?
**Answer:** Qoder versions 0.1.20, 0.1.21, 0.1.22, 0.1.23, 0.2.1 and 0.2.2 are officially supported.

### 5. How does this thing work?
**Answer:** It modifies a specific address (machineId address) using memory manipulation to change it to a random UUID value, effectively spoofing your machine identity to Qoder.

## Support

This tool is designed for Windows only. macOS users are not supported.

---

**Disclaimer**: This tool is for educational purposes. Use responsibly and in accordance with applicable terms of service.
