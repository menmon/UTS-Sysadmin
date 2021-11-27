# **UTS Sistem Administrasi Server**



Nama : M. Qoidul Ghuril

NIM    : 1202190025

Kelas  : IT 02 02



### **Virtual Installation Windows Server 2022**

------



- ###### Download ISO  Windows Server 2022 




- ​	Open Windows Server 2022 With Link: https://www.microsoft.com/en-us/ev	alcenter/evaluate-windows-server-2022

  

  - ​	Then we will see like this



​		![1](https://user-images.githubusercontent.com/51281505/143685420-7c06cad3-cbb7-4f69-8f65-a7fda03240f9.PNG)



​			Then fill this documentary



![2](https://user-images.githubusercontent.com/51281505/143685421-8db11645-9f16-4c97-8615-f1c50e923f3a.PNG)



- ###### Install Windows Virtual Server 2022 Using Virtual Box

  - Open Virtual Box and Click "New"
  - 
  
  ![3 5](https://user-images.githubusercontent.com/51281505/143685581-5d86c68a-6f9f-443f-94d4-ab69c90a458c.PNG)
  
  
  
  - Enter The Name Of Virtual OS
  
  
  
  ![3](https://user-images.githubusercontent.com/51281505/143685422-372bec33-e441-4d37-bee2-5ba8c73bf181.PNG)
  
  
  
  - Select The Mount Size Of RAM Then 
  
  
  
  ![4](https://user-images.githubusercontent.com/51281505/143685425-413dbe14-e928-4cb2-82a7-1b988ef7a33d.PNG)
  
  
  
  - Select The Option of  "Create a virtual hard disk now"
  
  
  
  ![5](https://user-images.githubusercontent.com/51281505/143685426-72bd828a-dbee-44d1-ada5-a29588549724.PNG)
  
  
  
  - Select The Type of Disk We Should Choose "VDI"
  
  
  
  ![6](https://user-images.githubusercontent.com/51281505/143685427-20f151b4-f34e-4ed8-8025-c6be45359981.PNG)
  
  
  
  
  
  - For The Hard Disk Option We Should Choose "Dynamically allocated"
  
  
  
  ![7](https://user-images.githubusercontent.com/51281505/143685432-dda94ece-cf17-4bab-b02b-49461b651c6c.PNG)
  
  
  
  - Select The Size of Virtual Hard Disk
  
  
  
  ![8](https://user-images.githubusercontent.com/51281505/143685437-7ab4b052-fb1a-4ac5-93ae-2ed7a893ddcc.PNG)
  
  
  
  - Before We Launch it, Open  Virtual Box "Setting" Then Choose "Network" Change The "Network" Setting to "Bridge Adapter".
  
  
  
  ![4 5](https://user-images.githubusercontent.com/51281505/143685424-575def17-aef9-4b34-96f9-2f95205638c2.PNG)
  
  
  
  - Launch Virtual OS in The Virtual Box and Find ISO Windows Server to Install it. 
  
  
  
  ![11](https://user-images.githubusercontent.com/51281505/143685441-576d1b62-1a70-48e4-8b4a-3a6b144874a6.PNG)
  
  
  
  - Choose Your Language
  
  
  
  ![12](https://user-images.githubusercontent.com/51281505/143685442-d4825f74-90c3-4b7e-b19d-96d4894f2245.PNG)
  
  
  
  - Then Click "Install Now"
  
  
  
  ![13](https://user-images.githubusercontent.com/51281505/143685443-68ccc708-d7f4-4e0b-a5cb-ec9f5affadb6.PNG)
  
  
  
  - Choose The GUI(I Choose "Windows Server 2022 Datacenter Evaluation(Destop Experience)")
  
  
  
  ![14](https://user-images.githubusercontent.com/51281505/143685445-2612f187-ff89-4e83-9c59-d3008fa3b8f1.PNG)
  
  
  
  - Click  license terms then click "Next"
  
  
  
  ![15](https://user-images.githubusercontent.com/51281505/143685446-3bb5601e-00d7-46a5-9f75-f741600c37be.PNG)
  
  
  
  - I Choose "Custom: Install Windows only (advanced)"
  
  
  
  ![16](https://user-images.githubusercontent.com/51281505/143685448-025839c9-316f-48ec-847a-7070bbf561b7.PNG)
  
  
  
  - Select the partition, Then click "Next"
  
  
  
  ![17](https://user-images.githubusercontent.com/51281505/143685449-968bb656-ac3d-4e3b-a024-a268201a3a08.PNG)
  
  
  
  - Wait For The Installation Processing
  
  
  
  ![18](https://user-images.githubusercontent.com/51281505/143685450-d79c6395-c03f-4204-850b-c93c9c43930e.PNG)
  
  
  
  - After Finish Installation. Configure the Administrator password Then click "Finish"
  
  
  
  ![19](https://user-images.githubusercontent.com/51281505/143685453-d8c21dbd-0f20-4250-82b2-8cf0185da099.PNG)
  
  
  
  - To login as Administrator, press the combination on the keyboard **Ctrl + Alt + Del** or In Keyboard Key in The Top of VIrtual OS
  
  
  
  ![21](https://user-images.githubusercontent.com/51281505/143685455-dd52e4cb-b739-44e5-9651-d0575ef703a4.PNG)
  
  
  
  - Input The Password



![22](https://user-images.githubusercontent.com/51281505/143685463-ea22f8a1-849b-4e6c-82ba-5c6b8d6eed15.PNG)



​		Installation Complete



​		![23](https://user-images.githubusercontent.com/51281505/143685468-d83ddf0b-83d1-4c3e-a8c7-beeb9347fa7d.PNG)



- #### Installation Active Directory Domain Services

  - Rename Computer with PowerShell Run as Administrator, Then type `rename-computer -Newname Server22`

  

  ![24](https://user-images.githubusercontent.com/51281505/143685469-4cdac396-e894-4fe8-a647-44731f6dcac5.PNG)

  

  - Open "Server Manager" menu.Select the “Manage” option then click “Add Roles and Features”. Then click “Next”

  

  ![25](https://user-images.githubusercontent.com/51281505/143685470-89ed3992-37a0-4a06-9bb9-9f23ec09d394.PNG)

  

  - Choose “Role-based or feature-based installation”. Then Click “Next”

  

  ![27](https://user-images.githubusercontent.com/51281505/143685476-f0b1faf0-8fff-4767-a01b-947e1f863448.PNG)

  

  - Choose “Select a server from the server pool” , Then Click "Next"

  

  ![28](https://user-images.githubusercontent.com/51281505/143685478-d2fdd0a8-0f39-4791-b075-d63fdfc13fdd.PNG)

  

  - Click the "Active Directory Domain Services" box. When you click the box, a description of A.D.D.S appears and how it to use it. Then click "Add Feature", Then Click "Next"

  

  ![29](https://user-images.githubusercontent.com/51281505/143685480-e3d428b8-f743-4888-863f-805c89034ca0.PNG)

  

  - Then just click next for this step

  

  ![30](https://user-images.githubusercontent.com/51281505/143685482-21a5fb7f-1628-4954-b905-d848c75d0bfb.PNG)

  

  - Click Next again

  

  ![31](https://user-images.githubusercontent.com/51281505/143685487-73f66d99-1827-49fb-b456-a40d6655235d.PNG)

  

  - Click Install 

  

  ![32](https://user-images.githubusercontent.com/51281505/143685489-23b9b39c-301a-482c-979b-ee8038322ece.PNG)

  

  - Wait for Installation

  

  ![33](https://user-images.githubusercontent.com/51281505/143685492-ba5695a9-e660-4e8b-9eea-76c000edf85d.PNG)

  

  

  - Installation Complete Congratulation

  









​		