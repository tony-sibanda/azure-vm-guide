# Creating a Windows Virtual Machine in Azure

This guide walks you through the steps to create a Windows Virtual Machine (VM) in Microsoft Azure using the Azure Portal.

---

## 1. Log in to the Azure Portal

Go to [https://portal.azure.com](https://portal.azure.com) and sign in with your credentials.

---

## 2. Search for Virtual Machines

In the top search bar, type “Virtual Machines” and select the **Virtual Machines** service.

![Search Virtual Machines](images/Screenshot%20VM%202.png)

---

## 3. Click “Create” → “Azure Virtual Machine”

![Click Create VM](images/Screenshot%20VM%205.png)

---

## 4. Configure Basic Settings

Choose the following:

- **Subscription**: Your subscription
- **Resource group**: Create a new one or use an existing
- **Virtual machine name**: e.g., `MyWindowsVM`
- **Region**: Select closest region
- **Image**: Windows 10 Pro (or equivalent)
- **Size**: Choose a size with at least 2 vCPUs
- **Username/Password**: Create login credentials

![Basic Settings](images/Screenshot%20VM%2010.png)

---

## 5. Configure Disks and Networking

- **Disk**: Use Standard SSD
- **Networking**: Leave default or create a new VNet

![Networking](images/Screenshot%20VM%2011.png)

---

## 6. Management, Monitoring, Advanced

Leave these with default settings unless you need customization.

![Management Tab](images/Screenshot%20VM%2012.png)

---

## 7. Review + Create

Azure will validate your settings. Once validated:

- Click **Create** to deploy the VM.

![Review and Create](images/Screenshot%20VM%2014.png)

---

## 8. VM Deployment

After deployment finishes, go to the **Virtual Machines** dashboard to view and manage your new VM.

![Deployment Complete](images/Screenshot%20VM%2018.png)

---

## 9. Connect to Your VM

Click your VM name, then **Connect** → **RDP**. Download the `.rdp` file and open it.

![Connect to VM](images/Screenshot%20VM%2019.png)

---

## 10. Access and Use Your VM

Once connected, you can use the VM like a regular Windows machine in the cloud.

![Windows VM in Azure](images/Screenshot%20VM%2030.png)

---

## ✅ Summary

You’ve successfully created and connected to a Windows VM using the Azure Portal.

For more guides like this, visit [https://github.com/tony-sibanda](https://github.com/tony-sibanda)
