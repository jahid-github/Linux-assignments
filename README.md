                                        Assingment 1 - Virtual Machine creation

                                          Step 1: Create an Azure Account
Went to Azure Portal and Register for a free account using my HAMK student email. Activated my Azure for Students subscription by visiting Azure for Students and signing up with my student email.

                                          Step 2: Create a Virtual Machine
- Logged in to the Azure Portal.
- On the homepage, clicked Create a resource > Compute > Virtual Machine.
- Virtual Machine Settings:
Selected Ubuntu Server 24.04 LTS Gen 2 published by Canonical and gave name Ubuntu1-tja-NEur-B1s.
Size: B2ls_v2.
Authentication Type:
SSH Public Key
Public IP Address: Enabled it to allow SSH traffic.
Resource Group: Created a new resource group
Subnet: Created a new subnet in the same resource group.

                                        Step 3: Connect to the Virtual Machine
After deployment is successful, went to the virtual machine in Azure.
Copied the public IP address from the virtual machine's overview page.
Connected via SSH:
Downloaded PuTTY from the official site. Installed the 64-bit MSI package.
Opened PuTTY:
Entered the public IP address (74.234.35.58) of my virtual machine.
Clicked Open to establish the connection.
Logged in using the username and authentication method specified during VM creation.

**THE END**
