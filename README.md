# df-mod3-sdm

#Exercise1
##Using "Get-WinEvent -ListLog * > logs.txt" and "Get-Content logs.txt | Select-String "VPN"" I was able to look at logs from my PC and then look at parts of my logs that only contain VPN in them. 
###This is useful because I can look for important logs on someone elses or my own computer, and then use a system to sort through it and look for keywords which can save a lot of time if it has too many logs.
#Exercise2
##Using "mkdir C:\Users\Sethe\Desktop\df-mod3-sdm\New" I was able to make a new directory to put all of my files into. I can copy files from other places on my PC and put them into this new directory or folder. After doing this I can also look at the Access Control List of my files and view all of the information attached. Using Get-Acl I can create another file with Export-CSV to make a physical copy of who is able to look at files.
#Exercise3
##In this exercise I used Get-Acl again and also icacls, I used Get-ACL to yet again view my ACL, but using icacls I managed the permissions of files. 

