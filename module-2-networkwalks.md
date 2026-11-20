# Module 2: Password Cracking with Networkwalks Tools

## Objective
Recover the password of another locked PDF (`My Locked PDF1.pdf`) using Networkwalks'
browser-based Hash Calculator and Password Cracker tools, with no local install required.

## Step 1: Extract the hash
Uploaded the locked PDF to the Networkwalks Hash Calculator to generate the `$pdf$...` hash.

![](https://github.com/deemanuel2/Password-cracking-with-John-the-Ripper-and-Networkwalks-Tools/blob/4bcdaac143da070eae9f1dd176436f9c9e8b07c0/hash_value_2.png)

## Step 2: Run the Password Cracker
Pasted the hash into the Networkwalks Password Cracker and ran the dictionary attack
using the tool's built-in wordlist.

![](https://github.com/deemanuel2/Password-cracking-with-John-the-Ripper-and-Networkwalks-Tools/blob/ab2d8cc565d2e358c5a0e18f570995f98af497d7/cracked_pdf_2_password.png)

## Step 3: Confirm the result
Opened the PDF with the recovered password and confirmed it opened successfully /
confirmed the captured flag.

**[Screenshot: PDF opened with recovered password]**

## Result
Password for `My Locked PDF1.pdf` successfully recovered using the Networkwalks
Hash Calculator and Password Cracker, confirming the same outcome as Module 1 via a
browser-only workflow.
