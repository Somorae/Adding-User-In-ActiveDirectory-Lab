# 👥 Active Directory: Creating a New User (AWS Lab)

## 🎬 Watch Me Build This Lab!
https://www.loom.com/share/1c4307d833a64c91b075adcb339e5bb3

## 🎯 Objective
Demonstrate the creation and configuration of a new domain user account using **Active Directory (AD)** on a Windows Server hosted in AWS.

## 🛠️ Tools 
- AWS EC2 (Windows Server)
- Active Directory Domain Services (AD DS)
- Active Directory Users and Computers (ADUC)
- Windows Server

## 📝 Steps Performed 
1. Logged into the EC2 Windows Server instance.
2. Opened **Active Directory Users and Computers** from the Windows search bar.
<img width="954" height="579" alt="Reset Ad step 2" src="https://github.com/user-attachments/assets/e7e240a7-a154-4f8c-ab08-5df6391c101e" />

3. Expanded the **skool.local** domain.
4. Right-clicked the **Users** container and selected **New → User**.
<img width="698" height="445" alt="User step 3" src="https://github.com/user-attachments/assets/1a082dd4-d0ed-4d4e-84b7-68a09c9ab5a0" />

5. Entered the user’s name **Jane Doe** and assigned a login name.
6. Clicked **Next**, then created and confirmed a password.
<img width="608" height="370" alt="User step 4" src="https://github.com/user-attachments/assets/e5e5539c-5c4d-4881-80bc-c303025393b1" />

7. Deselected **User must change password at next logon**.
8. Selected **Password never expires**.
9. Clicked **Next**
<img width="632" height="365" alt="User step 5 " src="https://github.com/user-attachments/assets/d7817d5f-721a-4cf5-848c-59a2bd53085e" />

10.   **Finish** to complete user creation.
<img width="593" height="377" alt="User step 6" src="https://github.com/user-attachments/assets/54307169-e7be-4f7a-b268-da80e4db820a" />

<img width="583" height="362" alt="User step 7" src="https://github.com/user-attachments/assets/9cc33144-e9f7-4780-9948-9c297875409a" />


## ✅ Outcome
The domain user **Jane Doe** was successfully created and configured in Active Directory, validating proper user provisioning and account policy management within the AWS-hosted Windows Server environment.

## 📌 Key Skills Demonstrated
- Active Directory user provisioning
- Account policy configuration
- Windows Server administration
- AWS EC2 Windows environments
- Identity and access management (IAM fundamentals)


