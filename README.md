# Windows-Kernel-Driver-Development
Windows Kernel Driver Development

Set up Enviroment : 

| Host  | Virtual |
| ------------- | ------------- |
| Visual Stduio 2019 Community  | Vmware - Windows 10 x64 (Fireeye Flare)  |
| Windows Driver Kit (WDK)  | DebugView  |
| Visual Stduio 2019 Community  | Windbg  |
| Windows Software Development Kit (SDK)  |   |
| VirtualKD-Redux (vmmon**) | VirtualKD-Redux (targetx**)|


Reference : https://docs.microsoft.com/en-us/windows-hardware/drivers/download-the-wdk

Notice for Virtual Machine : 

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Debug Print Filter DEFAULT : REG_DWORD : 0xFFFFFFFF
https://stackoverflow.com/questions/12494300/no-output-from-debugview

![image](https://user-images.githubusercontent.com/10811344/131552984-5e07bc5f-8d39-4ba0-b00f-7957d366334c.png)

Windows Driver Loader : 

https://www.osronline.com/article.cfm%5Earticle=157.htm

If you want to kernel debugging on virtualbox/vmware, you can download virtualkd : 

https://sysprogs.com/legacy/virtualkd/
https://github.com/4d61726b/VirtualKD-Redux (Vmware 16 - I am using)

I am using vmware and I will follow that instructions : 

![image](https://user-images.githubusercontent.com/10811344/131564967-69054217-2176-4139-abb2-30eaef0bc1d0.png)

![image](https://user-images.githubusercontent.com/10811344/131565123-f5496b9f-ccca-45dc-9e6b-a710e6f3eb1c.png)

![image](https://user-images.githubusercontent.com/10811344/131565185-def3f7c9-87ba-4da7-87aa-1ba85f17eed3.png)



Extract VirtualKD and copy "target" file to virtual machine and as run as admistrator
F8-Disable Driver Signature Enforcement (VDK-Redux)
Restart to Virtual Machine
Restart to Host Machine

https://github.com/4d61726b/VirtualKD-Redux/blob/master/VirtualKD-Redux/Docs/Tutorial.md
 
