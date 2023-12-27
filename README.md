# ESXi and vSphere Client Configuration

## Lab Overview

This lab guides students through setting up VMware ESXi as a virtualization platform and managing it using the vSphere Client. Students will configure ESXi hosts, install the vSphere Client, create users, assign permissions, and understand virtual machine and resource pool management.

## Lab Tasks and Screenshots

### 1. Create and Configure ESXi VM in Workstation

Create a new ESXi VM and configure it with proper settings including network and storage.

- **Screenshot 1**: Capture of the final ESXi VM configuration showing network settings and successful installation.
  <img src="https://i.imgur.com/yH5IN62.png" height="400px" width="auto" alt="ESXi VM Configuration"/>

### 2. Install the vSphere Client on Windows 7 VM

Install the vSphere Client and connect to the ESXi host, showcasing the initial setup and connectivity.

- **Screenshot 2**: Capture of vSphere Client connected to the ESXi host, showing the main console with the host visible.
  <img src="https://i.imgur.com/8bi9Spt.png" height="400px" width="auto" alt="vSphere Client Connectivity"/>

### 3. Create a User and Assign Permissions

Create a user in ESXi/vSphere and assign appropriate permissions for access control.

- **Screenshot 3**: Capture of the user creation process and the permissions assigned to this user in vSphere.
  <img src="https://i.imgur.com/3DDhJYG.png" height="400px" width="auto" alt="User Creation and Permissions"/>

### Explanation
The attempt to assign additional permissions failed because the "Power State" role assigned to the user only allows for powering the VM on and off, and doesn't include permissions for other actions or modifications to the VM.

### 4. Modify Permissions and Access SSH

Modify permissions on resource pools and VMs. Also, include enabling and accessing SSH on the ESXi host.

- **Screenshot 4**: Capture of the modified permissions for resource pools and VMs, and the SSH session into ESXi showing the user logged in.
  <img src="https://i.imgur.com/RRnKetZ.png" height="400px" width="auto" alt="Modified Permissions and SSH Access"/>


