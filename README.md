# Password Cracking with John the Ripper and Networkwalks Tools

## Overview
This project covers two password cracking exercises. The two exercises each target
a separate password-protected PDF file — `My Locked PDF1.pdf`, cracked using John the
Ripper and Johnny, and `My Locked PDF1 For NW Tools lab WK3-PM2.pdf`, cracked using
Networkwalks' browser-based tools. Both recover the file's password using a hash
extraction and dictionary attack workflow.

## Objective
Demonstrate the ability to extract a password hash from a protected file and recover
the original password using both a standalone cracking tool (John the Ripper) and a
browser-based cracking tool built by Networkwalks.

## Tools Used
| Tool | Purpose |
|------|---------|
| John the Ripper (John) | Command-line password hash cracking |
| Johnny | GUI front-end for John the Ripper |
| Online Hash Crack | Extracted the `$pdf$...` hash from the PDF |
| Networkwalks Hash Calculator | Browser-based PDF hash extraction |
| Networkwalks Password Cracker | Browser-based dictionary attack on the hash |
| [PDF viewer] | Opened and verified the unlocked PDFs |

## Tasks Completed
- [x] Module 1: Cracked `My Locked PDF1.pdf` using John the Ripper (CLI) and Johnny (GUI)
- [x] Module 2: Cracked `My Locked PDF1 For NW Tools lab WK3-PM2.pdf` using Networkwalks' online Hash Calculator + Password Cracker

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
