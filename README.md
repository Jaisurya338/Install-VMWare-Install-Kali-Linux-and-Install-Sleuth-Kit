# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: Ramesh Jaisurya
### Reg No:212225240117
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version
   


## OUTPUT:
**VIRTUAL BOX:**
<img width="1720" height="880" alt="Screenshot (125)" src="https://github.com/user-attachments/assets/1b85b41b-837e-4cb3-9d20-1a42f92f16a3" />

**KALI LINUX:**
<img width="1720" height="880" alt="Screenshot 2026-08-24 233230" src="https://github.com/user-attachments/assets/63d598f8-3a6e-4519-88a5-131b5c81eb9d" />

<img width="1495" height="929" alt="Screenshot 2026-08-24 230355" src="https://github.com/user-attachments/assets/449fbe68-2fc2-4d22-83d4-3436f690407e" />

**SLEUTH-KIT:**
<img width="1720" height="880" alt="Screenshot 2026-08-24 232843" src="https://github.com/user-attachments/assets/694b5204-5fff-49f2-a5f0-cd92e8078102" />

## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
