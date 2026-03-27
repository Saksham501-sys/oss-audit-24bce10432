#Open Source Audit Project
Name: Saksham Agrawal
Registration Number: 24BCE10432
Open Source Software

#What I Chose
I'm looking at Python. It’s an open-source language that people love because it’s easy to read and has a massive community behind it.

#Project Overview
This project breaks down Python from an open-source angle. I’ve also included five shell scripts to show how Linux works in practice. It’s a mix of theory and actually getting your hands dirty with code.

#The Scripts
Script 1: Pulls up system info. You'll see the kernel, user, uptime, and the OS version.

Script 2: Checks if Python is actually there and lists the package details.

Script 3: This one audits your directories. It looks at permissions and how much disk space you’re using.

Script 4: Scans log files. It finds specific keywords and counts how many times they pop up.

Script 5: Creates a personalized open-source manifesto.

#Running the Code
First, you need to make the files executable. Run this:
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh

#Now you can run them one by one:
./script1.sh
./script2.sh
./script3.sh
./script4.sh /var/log/syslog error
./script5.sh

#What You Need
You’ll need a Linux OS and the Bash shell. It relies on standard commands like uname, dpkg, and grep.

#Final Thoughts
This project covers the basics of open-source ideas. It’s a simple way to show how Linux scripting works with Python as the main focus. It does the job.
