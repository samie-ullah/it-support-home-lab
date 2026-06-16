# IT Support Troubleshooting Scenarios

## Scenario 1: Group Policy Not Applying
- Issue: gpupdate /force failing
- Cause: Time synchronisation drift causing Kerberos authentication failure
- Resolution: Corrected system time and verified Domain Controller as time source
- Result: Group Policy applied successfully

## Scenario 2: Account Lockout
- Issue: User unable to log in
- Investigation: Event Viewer (Event ID 4740)
- Resolution: Account unlocked and password reset
- Result: User logged in successfully

## Scenario 3: VPN Connectivity Failure
- Issue: VPN connection failing or dropping
- Cause: Firewall profile and NAT loopback issues
- Resolution: Corrected firewall configuration and routing
- Result: Successful VPN connection

## Scenario 4: File Server Access Denied
- Issue: User unable to access department folder
- Cause: Incorrect NTFS permissions or missing group membership
- Resolution: Updated AD group membership and NTFS permissions
- Result: User gained correct access
