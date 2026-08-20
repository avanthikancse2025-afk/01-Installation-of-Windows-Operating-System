# Experiment 1: Installation of Windows Operating System

## Aim

To install the Windows Operating System on a computer system and verify the successful installation using basic system commands.

---

## Requirements

* Computer/Laptop
* Windows Operating System installation media
* Bootable USB drive or Windows installation media
* Keyboard and mouse
* Sufficient storage space

---

## Procedure

### Step 1: Prepare the Installation Media

Create or obtain a bootable USB drive containing the Windows Operating System installation files.

### Step 2: Boot from the Installation Media

Insert the bootable USB drive into the computer and restart the system. Enter the boot menu or BIOS/UEFI settings and select the USB drive as the boot device.

### Step 3: Start Windows Setup

When the Windows Setup screen appears, select the required:

* Language
* Time and currency format
* Keyboard/input method

Click **Next** and then select **Install Now**.

### Step 4: Select the Installation Type

Choose the appropriate installation option. For a fresh installation, select **Custom: Install Windows only**.

### Step 5: Select the Installation Drive

Select the required disk partition for Windows installation and proceed with the installation.

The setup process will copy the required files and automatically restart the computer several times.

### Step 6: Complete Windows Configuration

After installation, complete the initial Windows configuration, including:

* Region selection
* Keyboard layout
* User account creation
* Network configuration
* Privacy and security settings

### Step 7: Verify the Installation

After reaching the Windows desktop, open **Command Prompt** and execute the following commands to verify the operating system and system configuration.

---

## Verification Commands

### 1. Check Windows Version

```cmd
winver
```

This command displays the installed Windows version and build information.

### 2. Display System Information

```cmd
systeminfo
```

This command displays detailed information about the operating system, processor, memory, system manufacturer and other configuration details.

### 3. Check Computer Name

```cmd
hostname
```

This command displays the name assigned to the computer.

### 4. Check IP Configuration

```cmd
ipconfig
```

This command displays the network configuration, including the IP address and other network information.

---

## Result

The Windows Operating System was successfully installed and the installation was verified using the `winver`, `systeminfo`, `hostname`, and `ipconfig` commands.

---

## Conclusion

Thus, the Windows Operating System installation process was successfully completed and the basic system configuration was verified using Command Prompt.
