# Metadata-Extraction-using-ExifTool-log2timeline-and-Hidden-Data-Search-using-Steganography-Tools
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

## Extracted Metadata:

![dfdi 06](https://github.com/user-attachments/assets/3aa039fb-5138-4599-9b6a-b657923a0447)


## Embed data, Extraction data, Binwalk For Analysis:

![dfdi 06(1)](https://github.com/user-attachments/assets/22939494-01fe-4d57-b2ec-f0b09c5dc1a6)

## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

