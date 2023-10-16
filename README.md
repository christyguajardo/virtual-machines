'🖥️:' 
Setting up a virtual machine (VM) in Microsoft Azure involves several steps, from creating a virtual machine instance to configuring various settings. Here's a general guide on how to set up a virtual machine in Azure: 

1. Sign In to the Azure Portal:  '🚀

Go to the Azure portal (https://portal.azure.com) and sign in with your Azure account.
'📓Note: Sign up for the free 30 day period which includes a '💵$200 credit. A credit/debit card is needed to set up azure account. 

2. Create a New Virtual Machine: '🚀

 Click on "Create a resource" and select "Compute" > "Virtual machine."

 ![image](https://github.com/christyguajardo/azure-network-protocols/assets/147533626/0ee63b19-6df7-4ac6-a36a-3a697418cf64)

![image](https://github.com/christyguajardo/azure-network-protocols/assets/147533626/c9b40b26-ae27-4e25-8c58-6de741de25b9)
</p>
<br />


3. Configure Basics: '🚀

Fill in details for the virtual machine, including:

  '🪐 Subscription: Choose the subscription to use.
  
  '🪐 Resource group: Create a new one or use an existing group to organize related resources.
  
  '🪐 Virtual machine name: Provide a name for your VM.
  
  '🪐 Region: Select the region where you want to deploy the VM.
  
   Image: Choose a base image for the VM (e.g., Windows, Linux distributions).
   
  '🪐Size: Select the size for the VM based on your requirements.
  
![image](https://github.com/christyguajardo/azure-network-protocols/assets/147533626/d319ff54-bfe4-4101-a90f-429bf3e59bfc)
![image](https://github.com/christyguajardo/azure-network-protocols/assets/147533626/feb7ec24-2105-4226-8401-69adb1f38ba1)

 
4. Configure Administrator Account: '🚀

 Set the username and password for the administrator account or use SSH key for Linux VMs.
 
5. Configure Optional Features: '🚀

Configure optional features like:
  Public inbound ports: Allow specific inbound ports (e.g., 80 for HTTP, 443 for HTTPS).
  Disks: Configure OS disk settings.
  Networking: Set up networking configurations like virtual network, subnet, and public IP (if needed).
  
6. Tags (Optional): '🚀

Add tags to organize and manage your resources.

7. Review + Create: '🚀

Review the configuration settings and make any necessary adjustments.
Click "Create" to start the deployment process.

8. Wait for Deployment: '🚀

Azure will now deploy the virtual machine based on your configuration settings. This process may take a few minutes.

9. Access the Virtual Machine: '🚀

Once the VM is deployed, navigate to the Virtual Machines section in the Azure portal to access and manage your VM.
Connect to the Virtual Machine:

10. Use Remote Desktop Protocol (RDP) for Windows VMs or SSH for Linux VMs to connect to the VM and configure it according to your needs. '🚀
    
Remember to manage and secure your virtual machine properly by following Azure best practices, configuring security settings, and applying necessary updates and patches to maintain a secure environment. '💎





