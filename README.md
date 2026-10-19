# Active Directory IT Support Home Lab

## Project Overview

I built this virtual home lab using VMware Workstation to practice Windows Server administration and common IT support tasks. The lab includes Windows Server 2019 and a Windows 10 client connected to an Active Directory domain.

## Lab Environment

- Virtualization: VMware Workstation
- Server: Windows Server 2019
- Client: Windows 10
- Directory service: Active Directory Domain Services
- Shared folder: CompanyShare

## Tasks Completed

- Configured the Windows Server and Windows client lab.
- Set up Active Directory users and security groups.
- Joined the Windows 10 client to the domain.
- Successfully tested login using a domain user account.
- Created a shared folder named CompanyShare.
- Verified the share using the net share command.
- Accessed the shared folder from the Windows 10 client.
- Created and saved Client-Test.txt from the client to verify write access.
- Tested access using a separate user outside the intended authorized group; access was denied.
- Checked network connectivity using ping.
- Verified that the Windows Server service was running and set to start automatically.

## Troubleshooting

Initially, the Windows client could not access the shared folder. Ping to the server IP worked, and the Server service was running. I later gained access to the share and successfully created a test file. The exact cause of the initial error was not confirmed.

## Skills Practiced

- Windows Server administration
- Active Directory user and group management
- Domain account login testing
- SMB file sharing
- Share and NTFS permission concepts
- User access testing
- Basic network troubleshooting
- Technical documentation

## Screenshots

I will add screenshots documenting the virtual machines, Active Directory, DNS, shared-folder permissions, successful access, and unauthorized access testing.

## Security Note

Actual domain names, IP addresses, usernames, and passwords are not included in this documentation. Exact NTFS permission entries still need to be documented.

## Future Improvements

- Add screenshots of the completed lab.
- Document the exact share and NTFS permissions.
- Add a detailed test-results report.
- Continue practicing Windows troubleshooting and access control.
