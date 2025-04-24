# EXP 4 : USING THE AUTOPSY RETRIEVE THE DELETED FILES

## AIM:
This experiment aims to demonstrate:

  •	Create a Disk Partition.
  
  •	Adding, deleting, and recovering files using Autopsy.
  
  •	Understanding the forensic recovery of deleted data.
  
  •	Removing the disk partition after the process.

## EQUIPMENTS REQUIRED:
  ●	Hardware: PCs

```
Register Number:212223040171
Name: ROHAN J
```

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.


## PROCEDURE:
### Step1: Create a New Disk
  •	The new Disk Partition is created
  ![Screenshot 2025-04-23 220534](https://github.com/user-attachments/assets/01c81e93-de30-4de0-b863-d592574f5a04)


### Step2: Adding and Deleting Files for Recovery
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).
  
  •	Transfer images or files into it.
  ![Screenshot 2025-04-23 220816](https://github.com/user-attachments/assets/6d635770-dac0-4e22-83c4-c34721454241)

  
  •	Select one or more files → Press Delete.
  
  •	Empty the Recycle Bin to permanently remove them.
  
### Step3: Recovering Deleted Files Using Autopsy
1. Launch Autopsy and Set Up a New Case:
 
  •	Run Autopsy as Administrator.

  •	Click Create New Case.
  ![Screenshot 2025-04-23 140216](https://github.com/user-attachments/assets/749b7d31-2fea-400a-b215-c93cfa959930)


  •	Enter a case name (e.g., Autopsy1).
  
  •	Select a location for the case folder → Click Next → Finish.

  ![Screenshot 2025-04-23 140304](https://github.com/user-attachments/assets/4b48ea2f-ae4a-4644-be4c-fe4593df1ec9)

  

  •	Add optional information
  
  ![Screenshot 2025-04-23 140330](https://github.com/user-attachments/assets/dd820726-1486-427a-b100-e72f6a3d18d3)


2. Add the Partition as Evidence:
  •	Click Add Data Source → Choose Host.
![Screenshot 2025-04-23 140535](https://github.com/user-attachments/assets/5a658e66-889f-43d4-971f-c1e504e3070b)


  •	Select Local Disk → Click Next.Create a Disk Partition.
  ![Screenshot 2025-04-23 140543](https://github.com/user-attachments/assets/e4403945-c82d-4089-b9af-9d00540f6d21)


  •	Choose Disk → Select the VHD drive (Drive1).
  ![Screenshot 2025-04-23 140606](https://github.com/user-attachments/assets/0e4e9172-417b-42a8-bc54-a086fec79b69)


  •	Click Next → Keep the default settings → Click Finish.
  ![Screenshot 2025-04-23 140632](https://github.com/user-attachments/assets/b7525070-2680-40fa-83d4-6df2e2598f48)


  •	Allow Autopsy to process the disk.

## OUTPUT: Extract Deleted Files:
  •	In the left panel, navigate to File Views → Deleted Files.
  
  •	Locate your deleted images.
  ![Screenshot 2025-04-23 221341](https://github.com/user-attachments/assets/9e1ede33-e206-45ac-a876-792be533e116)


  •	Right-click an image → Click Extract File.
  
  •	Choose a folder for saving the recovered files (e.g., C:\image_recovery).
  
  •	The deleted images are now restored!
  ![Screenshot 2025-04-23 221841](https://github.com/user-attachments/assets/844dd780-5358-44a6-9057-c1ae83570e3d)


## Removing the Disk Partition (Optional Cleanup)
1.Using Disk Management:

  •	Open Disk Management (Win + X → Disk Management).
  
  •	Identify the created partition.
  
  •	Right-click on the partition → Select Delete Volume.
  
2.Alternative Method via Settings:

  •	Click the Start button → Go to Settings.
  
  •	Select System → Click Storage.
  
  •	Click Advanced Storage Settings → Select Disks & Volumes.
  
  •	View the list of available disks.
  
  •	Select the created partition → Click Properties.
  
  •	Click the Delete option to remove it.


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
