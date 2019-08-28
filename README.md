# Play-With-SSH
All command of SSH(Secure Shell) operations.

# 1. ZIP Operations
1.1 zip all files in the current directory
e.g zip filename.zip *
Note: In this subfolders & files will note includes and you can add file name without extension

1.2 zip-up an entire directory including all sub-directories
e.g zip -r filename *

# 2. UNZIP Operations
2.1 Unzip specific file 
e.g unzip filename.zip

# 3 Move files from One Server to another
For this, we will use SCP command and need both Servers IP Address, Username, Password and path to file or folder
3.1 Move file from the old server (A) to a new server (B) while logged into A
e.g scp path/to/file UsernameofB@IPofB:path/to/destination
e.g scp public_html/filename.zip yuvrajkhavad@192.111.1.1:public_html/newdata

Note: public_html/filename.zip:                     Server A Details 
      yuvrajkhavad@192.111.1.1:public_html/newdata: Server B Details 



.
.
.
.
.
.
.
.
Reference 
1. http://www.servermom.org/how-to-zip-compress-and-unzip-extract-files/
2. http://www.matrudev.com/post/transfer-files-web-server-using-ssh/
