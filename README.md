# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage

```
lsblk
```
````
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
````
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/48e85de6-81aa-4a5c-8024-322893c0b722)

![image](https://github.com/user-attachments/assets/224ffd6b-4852-49df-9c7f-9db10057fc06)

![image](https://github.com/user-attachments/assets/eb137d17-06a4-4584-acbb-d17d40284011)

![image](https://github.com/user-attachments/assets/8f3d7a68-ee1c-4a3e-91c4-ad49e8924f7b)

![image](https://github.com/user-attachments/assets/78c8b12e-52eb-4cc9-87fb-3373f7547880)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

