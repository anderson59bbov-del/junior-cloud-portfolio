 Charles Anderson Junior Cloud Engineer Portfolio

About This Portfolio

This repository documents my hands-on journey toward an entry-level cloud engineering role. I am building practical skills in Linux, networking, AWS, Python, and infrastructure as code.

My goal is to understand how systems work, troubleshoot problems methodically, and develop projects that demonstrate job-ready technical skills.

Current Learning Path

☑ Begin learning Linux fundamentals
☐ Practice Linux file navigation and directory management
☐ Understand file permissions
☐ Learn basic system troubleshooting
☐ Build networking fundamentals
☐ Develop AWS cloud skills
☐ Learn Python scripting
☐ Practice Terraform and infrastructure as code
Linux Labs

Lab 1: Linux Navigation and Files

Objective: Learn how to navigate the Linux filesystem and work with directories.

Commands studied:

Command

Purpose

pwd

Display the current working directory

ls

List files and directories

cd

Change directories

mkdir

Create a directory

touch

Create an empty file

cat

Display a file’s contents

Practice exercise:

mkdir -p ~/cloud-lab

cd ~/cloud-lab

pwd

mkdir practice

cd practice

touch notes.txt

ls

What I learned:

The Linux filesystem organizes files and directories in a hierarchy.
pwd helps identify my current location.
cd lets me move between directories.
mkdir and touch help create directories and files.
Verification: Record the output of pwd and ls after running the exercise.

Status: COMPLETED



Lab 2: Linux File Permissions

Objective: Understand how Linux controls access to files and directories.

Commands studied:

Command

Purpose

ls -l

Display files with permission details

chmod

Change file permissions

cat

Read file contents

echo

Print text or write text to a file

Practice exercise:

cd ~/cloud-lab

mkdir -p permissions

cd permissions

echo "Linux permissions practice" > example.txt

ls -l example.txt

chmod 600 example.txt

ls -l example.txt

What I learned:

Linux permissions control who can read, write, or execute a file.
chmod changes file permissions.
The > operator overwrites a file, while >> appends text.
The execute permission allows a file to be executed when applicable.
Security takeaway: Use the minimum permissions needed. For example, chmod 600 example.txt gives the file owner read and write access while removing permissions for group members and others.

Verification: Compare the output of ls -l example.txt before and after using chmod.

Status: COMPLETED



Lab 3: Linux System Troubleshooting

Objective: Learn basic commands used to inspect a Linux system before attempting to troubleshoot a problem.

Commands studied:

Command

Purpose

uname -a

Display kernel and system information

df -h

Check filesystem disk space

free -h

Display memory usage

ps aux

List running processes

whoami

Display the current username

pwd

Display the current directory

Practice exercise:

uname -a

df -h

free -h

ps aux

whoami

Create a basic troubleshooting report:

mkdir -p ~/cloud-lab/troubleshooting

cd ~/cloud-lab/troubleshooting



echo "Linux Troubleshooting Report" > report.txt

echo "Current user:" >> report.txt

whoami >> report.txt

echo "Current directory:" >> report.txt

pwd >> report.txt



cat report.txt

What I learned:

df -h helps identify filesystems that may be running out of disk space.
free -h helps inspect available and used memory.
ps aux helps identify running processes.
whoami and pwd provide useful context when diagnosing a problem.
Collecting information before making changes can reduce unnecessary or risky troubleshooting steps.
Verification: Review the command output and inspect the generated report.txt file.

Status: COMPLETED



Troubleshooting Notes

As I complete each lab, I will document:

The problem or task.
The commands used.
The actual output or result.
Any errors encountered and how I resolved them.
What I learned and how the skill applies to cloud infrastructure.
Next Steps

After validating these Linux labs, I plan to continue with networking fundamentals, AWS core services, Python automation, and Terraform.

This portfolio will grow as I complete practical exercises and projects.




