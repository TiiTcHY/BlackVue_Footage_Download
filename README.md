# BlackVue_Footage_Download
This script looks at the files on the camera and fulls the newest footage files available. This can be uploaded to a NAS drive to store the files.

## Usage
First, replace 'scriptpath', 'rootpath', 'folderpath', 'car' and 'ipaddress' with your actual file paths.

To run the script on Synology, use:
bash /volume1/Dashcam_Stuff/Scripts/Dashcam_File_Pull.sh

## Note
This will look at the dashcam and look for the latest files and download them to your NAS drive or your machine. It is recommneded that your schedule this to run on your NAS drive and schedule it to run every hour.
