# Linux Authentication Logs Study

## Objective
Understand how Linux authentication logs help security analysts monitor login activity and detect suspicious behavior.
## Topics Learned
- Authentication logs
- Failed login attempts
- User activity monitoring
- Security relevance of Linux logs

## Commands Explored
- cat
- grep
- tail
  
## Key Learning
Linux authentication logs can help identify:
- failed login attempts
- unauthorized access attempts
- suspicious authentication behavior

## Security Importance
Authentication logs are important in cybersecurity because they support:
- incident investigations
- monitoring activities
- security auditing
- brute-force detection

## Next Learning Goals
- Practice Linux commands
- Explore real authentication logs
- Learn SIEM log monitoring
- Understand SOC investigations
  
## Example Security Observation

Example authentication log:

Failed password for invalid user admin from 192.168.1.10

### Possible Security Analysis
- Multiple failed login attempts may indicate a brute-force attack
- Invalid user access attempts can indicate unauthorized access activity
- Repeated authentication failures should be investigated

### What To Investigate Next
- Check whether login attempts were successful later
- Verify whether the IP address is internal or external
- Identify whether multiple accounts were targeted
- Review account lockout events
