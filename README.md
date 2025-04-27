# Metadata-Extraction-using-ExifTool-log2timeline-and-Hidden-Data-Search-using-Steganography-Tools

# NAME:Moenish Baalan G
# REGISTER NO: 212223220057

## AIM:
To extract metadata, perform timeline analysis, and search for hidden data using forensic tools like ExifTool, log2timeline, and steganography detection tools.

## DESIGN STEPS:
### Step 1:
Use exiftool to extract metadata from files such as images, documents, and videos.

### Step 2:
Use log2timeline and plaso to create and analyze event timelines from system logs and file metadata.

### Step 3:
Apply steganography detection tools like steghide, zsteg, or binwalk to uncover hidden data in media files.

## PROGRAM:
Metadata and Timeline Forensics, Steganography Analysis Steps

# Installation :
```
   sudo apt update
   sudo apt install exiftool -y
   sudo apt install plaso -y
   sudo apt install steghide -y
   sudo apt install binwalk -y
```
# Extract metadata from a file:
```
  exiftool image path
  exiftool png.jpeg
```
# Embed data
```
steghide embed -cf (image path) -ef (text file path)
steghide embed -cf /home/bharathi/Downloads/png.jpeg -ef /home/bharathi/Downloads/hidden.txt
```
# Extract hidden data:
```
steghide extract -sf (imamge path)
steghide extract -sf png.jpeg
```
Using binwalk – for file analysis
```
 binwalk png.jpeg
```
## OUTPUT:
Extracted Metadata, Timeline Events, and Hidden Data Detection Results
# Extracted Metadata
![image](https://github.com/user-attachments/assets/37a73dae-434f-4d34-89b5-a298b1d5b3a6)


# Embed data and extraction of hidden data:
![image](https://github.com/user-attachments/assets/d2e73c23-3536-426e-8207-d4d6f7e4096d)


# using binwalk for analysis:
![image](https://github.com/user-attachments/assets/82dd71cd-68ec-46e9-a8e1-290a5f2e287d)



## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

