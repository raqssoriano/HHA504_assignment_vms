# Azure and GCP Virtual Machine Creation and Deletion and Cost Monitoring

## ▶︎ _**Virtual Machine**_
- ## *Creating VM in AZURE*
     <img width="1280" alt="Azure 1" src="https://github.com/user-attachments/assets/63140717-ccdc-4d03-8f0d-7b663eb4f0d2">


   ### ➤ As shown in the next two photos, I couldn't choose the Standard_B1ms - 1 vcpu, 2 GiB memory. It says "Request quota" on the side. The same issue happened with Standard_D2s_v3 -2 vcpus, 8 GiB memory. I just picked this one: Standard_DC1s_v2 - 1 vcpu, 4 GiB memory ($70.08/month), which is the lowest among the options I see.

     <img width="1277" alt="Azure 2" src="https://github.com/user-attachments/assets/cfcc2927-074c-4a60-8c48-b6821fb7102e">
     <img width="1279" alt="Azure 3" src="https://github.com/user-attachments/assets/c1e1427e-347a-4561-8440-fadde652f365">



     <img width="1278" alt="Azure 4" src="https://github.com/user-attachments/assets/f8daacb8-8a83-482f-a6b4-d5f1aef45366">



     <img width="1278" alt="Azure 5" src="https://github.com/user-attachments/assets/f6e5781b-eee6-4325-adf4-e12d5f4d899b">



     <img width="1280" alt="Azure 6" src="https://github.com/user-attachments/assets/1c5696f6-8e21-4824-8716-526fba5aa859">



   ### ➤ As shown in this photo, I encountered an error message and the creation of my VM was unsuccessful after clicking the Review + Create button. I clicked the arrow next to 'Click here to view details.'
     ![Azure 7](https://github.com/user-attachments/assets/432ebe4e-d7e3-47c5-8306-9ca86cad18ab)


   ### ➤ Then, the error message appeared, as shown in this photo.
     <img width="589" alt="Azure 8" src="https://github.com/user-attachments/assets/db3dcb98-51ba-42fe-98d7-8e203797f32a">


- ## *Creating VM in GCP*
   ### ➤ I navigated to Compute Engine ⇾ VM Instances, clicked 'Create Instance', created a new VM named 'gcp-vm-assignment', and picked the lowest memory under the Machine type. I waited for a minute or two before I saw a green check mark under status on the instances dashboard.

     <img width="1274" alt="GCP 1" src="https://github.com/user-attachments/assets/8a72e992-70be-4312-91f8-661dfcfef4c0">


     <img width="641" alt="GCP 2" src="https://github.com/user-attachments/assets/a05c3d32-a267-41db-bf90-c0d5f36f7797">


     <img width="1278" alt="GCP 3" src="https://github.com/user-attachments/assets/4026c018-6d6d-4fee-9ae2-9e1522fc3473">


     <img width="633" alt="GCP 4" src="https://github.com/user-attachments/assets/b1019ca3-dd69-476f-8057-87673a00b9d3">


     <img width="1279" alt="GCP 5" src="https://github.com/user-attachments/assets/7e6ac75b-d5d2-4827-9221-11a8c9af4bfa">



   ### ➤ After creating the VM, I clicked on it and explored the Details section for a few minutes. See photos below.
     <img width="1279" alt="GCP 6" src="https://github.com/user-attachments/assets/073e33ee-2bdf-485e-a332-a55294b58881">


     <img width="1278" alt="GCP 7" src="https://github.com/user-attachments/assets/5020ce87-6f89-476d-aacf-41bbda9831cd">


     <img width="1274" alt="GCP 8" src="https://github.com/user-attachments/assets/ab605a2f-e91c-4a6a-bbec-4b30f6fbb30c">



## ▶︎ _**Cost Monitoring**_
- ## *AZURE*
   ### ➤ As mentioned earlier, the creation of my VM was unsuccessful, making it impossible for me to check the associated cost.

- ## *GCP*
   ### ➤ I went to the Billing section and clicked on Reports. I don't see any amount associated with my new VM. I made sure that I haven't stopped or deleted it yet.

     <img width="1271" alt="GCP 9" src="https://github.com/user-attachments/assets/48f7541d-1b46-481a-8df5-bbefed0178c3">

   ### ➤ As I was exploring it, I found two ways to stop and delete the VM. See the photos below. First, on the dashboard under 'gcp-vm-assignment' (all the way to the right side), there are three vertically aligned dots. Second, after clicking the name of my VM, at the top almost to the right side, there are the same three vertically aligned dots. There are options to stop, delete, and several more.

   #### _Note:_ I stopped the VM before deleting it.
     <img width="1047" alt="GCP 10" src="https://github.com/user-attachments/assets/b8b936a5-a8cd-47ba-b83e-79b7a37056af">
     

     <img width="1272" alt="GCP 11" src="https://github.com/user-attachments/assets/8c8e41b0-41bd-4f99-84e7-51faa142bfe2">
     

     <img width="1275" alt="GCP 12" src="https://github.com/user-attachments/assets/2380e519-8200-4cfc-b369-daf729ff8094">
     

     <img width="1271" alt="GCP 13" src="https://github.com/user-attachments/assets/d60233b6-f682-4177-9e1d-b24a1fd0b127">
     

     <img width="1275" alt="GCP 14" src="https://github.com/user-attachments/assets/c9e77042-6678-4f13-b691-e1b7f5a87370">
     

     <img width="606" alt="GCP 15" src="https://github.com/user-attachments/assets/e1a4671f-4606-46b1-9cec-ed962688bc3d">
     
   ### ➤ I made sure I fully deleted the new VM I created by clicking the 'Refresh' button under the VM instances window, and I also used the refresh button on my Chrome browser.
     <img width="1177" alt="GCP 16" src="https://github.com/user-attachments/assets/79ed5372-6e2c-4642-8f2d-3dcf572e30ab">

# ▶︎ _**My Key Takeaways from this Assignment**_

### 📌  It's quite difficult to fully compare both Azure and GCP at this point because I haven't had the chance to successfully create a VM on Azure. I can only comment with GCP.

### 📌  With GCP, I find it easy to navigate and utilize its features when it comes to creating a VM and exploring the costs. Although it didn't allow me to see the exact costs associated with my new VM, I found it very straightforward.

### 📌  I hope I will still be able to successfully create a VM in the Azure environment. Personally, this time I like both, but for this assignment, I found GCP easier to navigate.
