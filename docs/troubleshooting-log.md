# Troubleshooting Log: Windows File Share

## Project Overview

This project involved troubleshooting and configuring file sharing between a Windows Server 2019 virtual machine and a domain-joined Windows 10 client using VMware Workstation.

## Problem

Initially, the Windows 10 client could not access the `CompanyShare` folder hosted on Windows Server 2019.

## Troubleshooting Process

### 1. Verified Network Connectivity

I used the `ping` command to test connectivity between the Windows 10 client and the server. The server responded successfully.

### 2. Verified the Shared Folder

I used the `net share` command on the server and confirmed that `CompanyShare` was listed as a shared resource.

### 3. Checked the Server Service

I verified that the Windows Server **Server** service was running and configured to start automatically.

### 4. Restored Shared Folder Access

After troubleshooting, I successfully accessed `CompanyShare` from the Windows 10 client.

### 5. Verified File Creation

I created and saved `Client-Test.txt` from the Windows 10 client inside the shared folder. This confirmed that the tested domain account had the necessary access to create files.

### 6. Tested Access Restrictions

I tested the share with a separate user outside the intended authorized group. Access was denied, demonstrating that the unauthorized-access test was successful.

## Final Results

| Test | Result |
|---|---|
| Network connectivity | Successful |
| Shared folder configuration | Verified |
| Server service | Running |
| Authorized client access | Successful |
| File creation from client | Successful |
| Unauthorized-user access test | Access denied |

## Conclusion

I successfully resolved the shared-folder access issue and verified communication between the Windows Server 2019 environment and the Windows 10 client. I tested file creation from an authorized account and confirmed that a separate unauthorized user was denied access.

This project strengthened my practical skills in Windows Server administration, Active Directory, network troubleshooting, SMB file sharing, and user access testing.

