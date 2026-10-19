# Active Directory IT Support Home Lab

## Project Overview

This project demonstrates my hands-on practice with Windows Server 2019, Active Directory, DNS, Windows 10 domain connectivity, and shared-folder access control. I built the lab using VMware Workstation to practice common IT support and Windows administration tasks.

## Lab Environment

- **Virtualization:** VMware Workstation
- **Server Operating System:** Windows Server 2019
- **Client Operating System:** Windows 10
- **Directory Service:** Active Directory Domain Services (AD DS)
- **DNS:** Domain name resolution
- **File Sharing:** SMB shared folder named `CompanyShare`

## Tasks Completed

- Configured a virtual Windows Server and Windows 10 client.
- Created and managed Active Directory users and security groups.
- Configured DNS and network settings for the lab.
- Joined the Windows 10 client to the Active Directory domain.
- Tested login using a domain user account.
- Created a shared folder named `CompanyShare`.
- Verified the shared folder using the `net share` command.
- Accessed the shared folder from the Windows 10 client.
- Created and saved `Client-Test.txt` from the client to test write access.
- Reviewed NTFS permissions for the shared folder.
- Tested access using a separate user outside the intended authorized group; access was denied.
- Used `ping` to test network connectivity.
- Verified that the Windows Server service was running and configured to start automatically.
- Troubleshot an initial shared-folder access issue and confirmed that access was subsequently working.

## Technical Skills Practiced

- Windows Server administration
- Active Directory user and group management
- Domain joining and domain account login testing
- DNS and basic network troubleshooting
- SMB file sharing
- Share and NTFS permissions
- User access verification
- Windows service management
- Troubleshooting and technical documentation

## Troubleshooting Experience

The Windows 10 client initially could not access `CompanyShare`. I checked network connectivity with `ping`, verified that the share existed using `net share`, and confirmed that the Windows Server service was running. I later restored access, successfully created a test file from the client, and tested access with a separate unauthorized user.

The exact cause of the original access problem was not confirmed, so I have documented the checks and verified results rather than assuming a root cause.

## Project Evidence

The lab evidence for this project includes screenshots of the virtual machines, server configuration, Active Directory, DNS, Windows 10 client, shared-folder write testing, NTFS permission review, and unauthorized-user access testing.

## Security Considerations

- Actual passwords are not included in this documentation.
- Screenshots should be reviewed to ensure they do not expose sensitive credentials or unnecessary personal information.
- Share permissions and NTFS permissions work together to determine access to shared files and folders.

## Project Summary

This lab provided practical experience with Windows administration and common IT support responsibilities, including account management, domain connectivity, shared-folder access, permission testing, and troubleshooting.
