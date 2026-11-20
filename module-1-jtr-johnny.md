# Module 1: Password Cracking with JTR (John + Johnny)

## Objective
Recover the password of a locked PDF (`My Locked PDF1.pdf`) using John the Ripper and
its GUI front-end, Johnny.

## Step 1: Set up John the Ripper in Johnny
Downloaded John the Ripper and the Johnny GUI from the official Openwall sources and
pointed Johnny to the `john.exe` executable.

## Step 2: Extract the password hash
Uploaded the locked PDF to an online PDF hash extractor to generate the `$pdf$...` hash.

![](https://github.com/deemanuel2/Password-cracking-with-John-the-Ripper-and-Networkwalks-Tools/blob/dd87ca9bc43614acd003e6e02c49815848f57834/Hash%20output.png)

## Step 3: Crack the password
Loaded the hash into Johnny and ran the attack. The password was recovered.

![](https://github.com/deemanuel2/Password-cracking-with-John-the-Ripper-and-Networkwalks-Tools/blob/ca93e271f67b30392fb9b498895eca57b2ebb8d3/Screenshot%202026-11-19%20152228.png)

## Step 4: Confirm the result
Opened the PDF with the recovered password and confirmed it opened successfully /
confirmed the captured flag.

![](https://github.com/deemanuel2/Password-cracking-with-John-the-Ripper-and-Networkwalks-Tools/blob/7a7daac11c7d89718ce3ffc35bbb90ce535ac964/cracked_pdf_output.png)

## Result
Password for `My Locked PDF1.pdf` successfully recovered using John the Ripper / Johnny.
