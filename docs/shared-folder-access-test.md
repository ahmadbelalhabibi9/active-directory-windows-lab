# Shared Folder Access Test Report

## Project Objective

The objective of this test was to verify shared-folder access between a Windows Server 2019 server and a domain-joined Windows 10 client.

## Test Environment

- Virtualization: VMware Workstation
- Server: Windows Server 2019
- Client: Windows 10
- Directory services: Active Directory
- Shared folder: `CompanyShare`

## Test Results

| Test | Expected Result | Actual Result |
|---|---|---|
| Verify shared folder | Share appears on the server | Successful |
| Verify network connectivity | Server responds to ping | Successful |
| Access share as authorized user | User can open the folder | Successful |
| Create a file from the client | File saves in the shared folder | Successful |
| Test unauthorized user | Access is denied | Access denied |

## Procedure

1. Verified that `CompanyShare` was listed using the `net share` command.
2. Tested connectivity between the client and server using `ping`.
3. Opened the shared folder from the Windows 10 client.
4. Created and saved `Client-Test.txt` from the client computer.
5. Tested access with a separate user outside the intended authorized group.

## Conclusion

The tests confirmed that the shared folder was accessible from the Windows 10 client and that the tested authorized account could create a file. The separate unauthorized-user test resulted in access being denied.

This exercise provided practical experience with Windows file sharing, Active Directory accounts, network connectivity, and access-control testing.
