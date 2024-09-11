# Azure and GCP Virtual Machine Creation and Deletion and Cost Monitoring

## ▶︎ _**Virtual Machine**_
- ## *Creating VM in AZURE*
     <img width="1280" alt="Azure 1" src="https://github.com/user-attachments/assets/b3ca2423-91f0-47ed-b33c-fbbf6eaccfac">



   ### ➤ As shown in the next two photos, I couldn't choose the Standard_B1ms - 1 vcpu, 2 GiB memory. It says "Request quota" on the side. The same issue happened with Standard_D2s_v3 -2 vcpus, 8 GiB memory. I just picked this one: Standard_DC1s_v2 - 1 vcpu, 4 GiB memory ($70.08/month), which is the lowest among the options I see.

     <img width="1277" alt="Azure 2" src="https://github.com/user-attachments/assets/325bcf37-cf64-42e3-9245-59f80abf91b3">

     <img width="1279" alt="Azure 3" src="https://github.com/user-attachments/assets/27c9b2bc-02e0-457a-a382-d653f7e28811">




     <img width="1278" alt="Azure 4" src="https://github.com/user-attachments/assets/42d96a5b-9c5e-4ca7-8d0c-d2d850021937">




     <img width="1278" alt="Azure 5" src="https://github.com/user-attachments/assets/ea2ffda0-b81b-4617-8073-372e2b4195b3">




     <img width="1279" alt="GCP 6" src="https://github.com/user-attachments/assets/86286292-7dee-4289-8935-151360cd2035">




   ### ➤ As shown in this photo, I encountered an error message and the creation of my VM was unsuccessful after clicking the Review + Create button. I clicked the arrow next to 'Click here to view details.'
     <img width="1279" alt="Azure 7" src="https://github.com/user-attachments/assets/9b2ec87e-7f62-452c-904b-312b580e5d02">



   ### ➤ Then, the error message appeared, as shown in this photo.
     <img width="589" alt="Azure 8" src="https://github.com/user-attachments/assets/637b0aef-21f3-48b7-8b2a-61b76836e1ba">



- ## *Creating VM in GCP*
   ### ➤ I navigated to Compute Engine ⇾ VM Instances, clicked 'Create Instance', created a new VM named 'gcp-vm-assignment', and picked the lowest memory under the Machine type. I waited for a minute or two before I saw a green check mark under status on the instances dashboard.

     <img width="1274" alt="GCP 1" src="https://github.com/user-attachments/assets/52266af9-f1f7-45a0-8975-5b16b4b9a9ed">



     <img width="641" alt="GCP 2" src="https://github.com/user-attachments/assets/29de93d5-ab0e-4791-a9ef-4c2eb0216086">



     <img width="1278" alt="GCP 3" src="https://github.com/user-attachments/assets/25a383da-dc4e-40cd-b598-e7d5d0fb135b">


     <img width="633" alt="GCP 4" src="https://github.com/user-attachments/assets/3d7203f5-99c7-4709-a192-8126a7914b39">



     <img width="1279" alt="GCP 5" src="https://github.com/user-attachments/assets/a74a1b99-e097-460b-8f6e-8e4259975686">



   ### ➤ After creating the VM, I clicked on it and explored the Details section for a few minutes. See photos below.
     <img width="1279" alt="GCP 6" src="https://github.com/user-attachments/assets/4506b4af-107b-4b7b-8fed-b85c3b4e45dd">



     <img width="1278" alt="GCP 7" src="https://github.com/user-attachments/assets/9a6fce98-f015-4026-873d-230cb0932c51">



     <img width="1274" alt="GCP 8" src="https://github.com/user-attachments/assets/b04a87b0-2ee5-4551-b9f5-b38deabd5c1d">




## ▶︎ _**Cost Monitoring**_
- ## *AZURE*
   ### ➤ As mentioned earlier, the creation of my VM was unsuccessful, making it impossible for me to check the associated cost.

- ## *GCP*
   ### ➤ I went to the Billing section and clicked on Reports. I don't see any amount associated with my new VM. I made sure that I haven't stopped or deleted it yet.

     <img width="1271" alt="GCP 9" src="https://github.com/user-attachments/assets/118ad75a-af1c-4630-9e5c-7cdc137da83b">

   ### ➤ As I was exploring it, I found two ways to stop and delete the VM. See the photos below. First, on the dashboard under 'gcp-vm-assignment' (all the way to the right side), there are three vertically aligned dots. Second, after clicking the name of my VM, at the top almost to the right side, there are the same three vertically aligned dots. There are options to stop, delete, and several more.

   #### _Note:_ I stopped the VM before deleting it.
     <img width="1047" alt="GCP 10" src="https://github.com/user-attachments/assets/9e3499a2-818d-4cfd-99a9-4a09f40f593f">

     

     <img width="1272" alt="GCP 11" src="https://github.com/user-attachments/assets/7dfeb31b-53c1-41ca-a921-1b362498c254">

     

    <img width="1275" alt="GCP 12" src="https://github.com/user-attachments/assets/b7ecbb52-f9ff-41ce-bcb9-8770d536fcfb">

     

     <img width="1271" alt="GCP 13" src="https://github.com/user-attachments/assets/1da0604d-d670-4681-808d-1e91e93470b1">

     

     <img width="1275" alt="GCP 14" src="https://github.com/user-attachments/assets/59081072-8e7c-4e9b-ab7d-469b2ae59931">

     

     <img width="606" alt="GCP 15" src="https://github.com/user-attachments/assets/0b3a2ad9-6ac4-420c-92dc-8d6bed2c6674">

     
   ### ➤ I made sure I fully deleted the new VM I created by clicking the 'Refresh' button under the VM instances window, and I also used the refresh button on my Chrome browser.
     <img width="1177" alt="GCP 16" src="https://github.com/user-attachments/assets/6bfb6504-eae5-4433-ab72-c494a03f4c68">

# ▶︎ _**My Key Takeaways from this Assignment**_

### 📌  It's quite difficult to fully compare both Azure and GCP at this point because I haven't had the chance to successfully create a VM on Azure. I can only comment with GCP.

### 📌  With GCP, I find it easy to navigate and utilize its features when it comes to creating a VM and exploring the costs. Although it didn't allow me to see the exact costs associated with my new VM, I found it very straightforward.

### 📌  I hope I will still be able to successfully create a VM in the Azure environment. Personally, this time I like both, but for this assignment, I found GCP easier to navigate.
