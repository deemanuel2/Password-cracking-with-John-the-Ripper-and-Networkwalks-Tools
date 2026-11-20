# Password Cracking with John the Ripper and Networkwalks Tools

## Overview
This project covers two password cracking exercises assigned during Week 3 of the
Networkwalks Cybersecurity & Ethical Hacking training. Both exercises target the same
password-protected PDF file (`My Locked PDF1.pdf`) and recover its password using a
hash extraction and dictionary attack workflow — once with a standalone tool, and once
with a browser-based tool.

## Objective
Demonstrate the ability to extract a password hash from a protected file and recover
the original password using both a standalone cracking tool (John the Ripper) and a
browser-based cracking tool built by Networkwalks.

## Tools Used
- John the Ripper (John + Johnny GUI)
- Online Hash Crack (PDF hash extractor)
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- [PDF viewer] (to open and verify the unlocked PDF)

## Tasks Completed
- [x] Module 1: Cracked `My Locked PDF1.pdf` using John the Ripper (CLI) and Johnny (GUI)
- [x] Module 2: Cracked `My Locked PDF1.pdf` using Networkwalks' online Hash Calculator + Password Cracker

## Key Takeaway
Both exercises recovered the password from a protected PDF within seconds using a
basic dictionary attack. This confirms a point every security team should
internalize: a short or common password offers no real protection against even
entry-level cracking tools. Strong, unique passwords and proper file encryption
remain the baseline defense against this kind of attack, not the exception.

## Disclaimer
This project was carried out in a controlled training environment using a file
provided for educational purposes. The techniques shown here should only be applied
to systems and files you own or have explicit written authorization to test.
