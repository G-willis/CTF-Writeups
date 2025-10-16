# TryHackMe: PowerShell Room

Date Completed: October 16, 2025  
Category: Windows / Command Line  
Difficulty: Beginner  
Platform: [TryHackMe](Windows PowerShell
tryhackme.com
Windows PowerShell)



# Overview

This room introduces **PowerShell**, a powerful command-line shell and scripting language developed by Microsoft. It’s commonly used by system administrators and security professionals to automate tasks, manage systems, and perform penetration testing on Windows environments.

Through this room, I learned how to navigate the PowerShell environment, execute cmdlets, and interact with the Windows operating system efficiently.



# Key Topics Covered

 Understanding the PowerShell environment  
 Cmdlets (`Get-Command`, `Get-Help`, `Get-Service`, `Get-Process`)  
 File system navigation (`cd`, `ls`, `pwd`)  
 Working with services and processes  
 Using pipelines and filtering (`|`, `Select-Object`, `Where-Object`)  
 Running scripts and managing execution policies  
 Remote management using `Invoke-Command`


# Commands Practiced

 List all cmdlets - `Get-Command` 
 Get help for a command - `Get-Help Get-Process` 
 View running processes - `Get-Process` 
 Check services status - `Get-Service` 
 Change directory - `Set-Location C:\` 
 Run remote command - `Invoke-Command -ComputerName RemotePC -ScriptBlock { Get-Service }` 


#  Takeaways

- PowerShell combines the flexibility of scripting with the power of the command line.  
- Cmdlets make automation easy and consistent.  
- Understanding PowerShell is essential for both **system administration** and **cybersecurity tasks** in Windows environments.


# 🔗 Room Link
🔗 [TryHackMe: PowerShell](Windows PowerShell
tryhackme.com
Windows PowerShell)


#  Next Step

Next, I’ll continue learning about **Windows privilege escalation** and **system exploitation** to deepen my skills in Windows environments.