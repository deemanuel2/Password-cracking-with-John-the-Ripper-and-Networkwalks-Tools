# Module 1: Password Cracking with JTR (John + Johnny)

## Objective
Recover the password of a locked PDF (`My Locked PDF1.pdf`) using John the Ripper and
its GUI front-end, Johnny.

## Step 1: Set up John the Ripper in Johnny
Downloaded John the Ripper and the Johnny GUI from the official Openwall sources and
pointed Johnny to the `john.exe` executable.

## Step 2: Extract the password hash
Uploaded the locked PDF to an online PDF hash extractor to generate the `$pdf$...` hash.

**[Screenshot: Hash extractor tool showing the extracted hash]**

## Step 3: Crack the password
Loaded the hash into Johnny and ran the attack. The password was recovered.

**[Screenshot: Johnny's Passwords tab showing the cracked password]**

> Note: Password value omitted from this write-up. See repo disclaimer — this is
> documented as a process, not as a credential dump.

## Step 4: Confirm the result
Opened the PDF with the recovered password and confirmed it opened successfully /
confirmed the captured flag.

**[Screenshot: PDF opened with recovered password]**

## Issue Encountered and Fix
*(Optional — fill this in if you hit a snag, e.g. Johnny not detecting john.exe until
the downloaded zip was fully extracted rather than browsed in place.)*

## Result
Password for `My Locked PDF1.pdf` successfully recovered using John the Ripper / Johnny.
