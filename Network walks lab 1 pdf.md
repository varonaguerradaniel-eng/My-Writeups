
## ==Tools Used==: 

**John the Ripper**

I had never used this tool before so I read this guide :
https://hackers-arise.com/password-cracking-getting-started-with-john-the-ripper/


## ==Lab Setup==:

**1 locked pdf**

I need to unlock them but I don't know the password, that's why I'm going to use ==John the Ripper==

==the task is==: recover the password of the locked PDF using Johnny

## Step 1:

I download the locked pdf to my **kali linux**. 

i used ==**pdf2john**== to extract the hash of the locked pdf 

```
pdf2john My-Locked-PDF1.pdf > hash_pdf.txt
```

and then I ran

```
john hash_pdf.txt
```

![[VirtualBox_kali-linux-2026.2-virtualbox-amd64_27_09_2026_22_52_24.png]]

the password for the locked pdf is : password1

![[VirtualBox_kali-linux-2026.2-virtualbox-amd64_27_09_2026_22_54_44.png]]