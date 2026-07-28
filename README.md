# ROS-Installation
how to install Robot Operating System

---

##  1. Execution Steps

### **Step 1: Setting up Ubuntu on WSL2**
* Installed the **Ubuntu 22.04 LTS** distribution via Windows PowerShell.
* Configured the initial Linux system user credentials and privileges.

### **Step 2: Repository & Key Configuration**
* Updated system dependencies and installed essential network/security utilities (`curl`).
* Downloaded and added the official ROS 2 GPG security key to authorize package installations.

### **Step 3: ROS 2 Package Installation**
* Refreshed package indices to register the newly added ROS 2 sources.

<img width="1275" height="715" alt="image" src="https://github.com/user-attachments/assets/994aafc5-1cf6-4042-96fb-e645b73660f2" />

### **Step 4: Environment Auto-Sourcing & Testing**
* Appended the ROS 2 environment startup script to the local `~/.bashrc` file for automatic loading upon terminal startup.
* Verified environment sourcing and active distribution parameters.

* <img width="1275" height="717" alt="image" src="https://github.com/user-attachments/assets/fbc19c95-5107-48fb-a4ba-5e1dc0ff411a" />


---

##  2. Challenges & Troubleshooting

* **Issue : Missing Environment File Warning**
  * **Cause:** Attempting to source the ROS setup script before completing the package installation.
  * **Solution:** Completed the full `ros-humble-desktop` package installation before sourcing the environment.


---

##  3. Verification
<img width="1449" height="786" alt="image" src="https://github.com/user-attachments/assets/56991500-9d63-4053-835e-b74c36c87b69" />
