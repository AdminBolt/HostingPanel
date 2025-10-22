# Security Policy

## 🔒 Reporting Security Vulnerabilities

The AdminBolt team takes security issues seriously. We appreciate your efforts to responsibly disclose your findings.

### Reporting a Vulnerability

**Please DO NOT report security vulnerabilities through public GitHub issues.**

Instead, please report them via email to:
- **Email**: contact@adminbolt.com

### What to Include

Please include the following information:

- Type of vulnerability
- Full paths of source file(s) related to the issue
- Location of the affected source code (tag/branch/commit or direct URL)
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### Response Timeline

- **Initial Response**: Within 24 hours
- **Status Update**: Within 72 hours
- **Resolution**: Varies based on severity

### Security Updates

Security updates are released as soon as possible after a vulnerability is confirmed. We follow this process:

1. Vulnerability is reported and confirmed
2. Fix is developed and tested
3. Security advisory is prepared
4. Update is released to all users
5. Public disclosure after users have time to update

## 🛡️ Security Features

AdminBolt includes several built-in security features:

### Authentication
- Two-factor authentication (2FA)
- Password strength enforcement
- Brute-force protection
- Session management
- IP-based access control

### Network Security
- Built-in firewall management
- DDoS protection integration
- SSL/TLS certificate automation
- Security headers configuration

### Application Security
- Input validation and sanitization
- SQL injection prevention
- XSS protection
- CSRF protection
- Security headers (CSP, HSTS, etc.)

### Server Security
- Regular security updates
- File integrity monitoring
- Malware scanning
- Security audit logging
- Rootkit detection

## 🔐 Best Practices

### For Administrators

1. **Keep AdminBolt Updated**: Always run the latest version
2. **Use Strong Passwords**: Enforce strong password policies
3. **Enable 2FA**: Require two-factor authentication
4. **Regular Backups**: Maintain automated backup schedules
5. **Monitor Logs**: Review security logs regularly
6. **Limit Access**: Use principle of least privilege
7. **Firewall Rules**: Configure restrictive firewall rules
8. **SSL/TLS**: Use HTTPS for all connections

### For Users

1. **Strong Passwords**: Use unique, complex passwords
2. **Enable 2FA**: Protect your account with two-factor authentication
3. **Secure FTP**: Use SFTP instead of FTP
4. **Regular Updates**: Keep your applications updated
5. **Backup Data**: Regularly backup your data
6. **Monitor Activity**: Review account activity logs

## 📋 Security Checklist

After installation, complete this security checklist:

- [ ] Change default admin password
- [ ] Enable two-factor authentication
- [ ] Configure firewall rules
- [ ] Enable SSL/TLS certificates
- [ ] Set up automated backups
- [ ] Configure security notifications
- [ ] Review and adjust file permissions
- [ ] Disable unnecessary services
- [ ] Configure fail2ban or similar
- [ ] Set up log monitoring

<!-- ## 🔄 Security Updates

Subscribe to security advisories:
- **RSS Feed**: https://adminbolt.com/security/feed
- **Email List**: security-announce@adminbolt.com
- **Twitter**: [@adminbolt_sec](https://twitter.com/adminbolt_sec) -->

<!-- ## 🏅 Acknowledgments

We maintain a Hall of Fame for security researchers who have helped improve AdminBolt's security:

https://adminbolt.com/security/hall-of-fame -->

## 📜 Disclosure Policy

- We follow a coordinated disclosure approach
- Public disclosure occurs after fix is deployed
- Credit is given to reporters (if desired)
- Severity ratings follow CVSS v3.1

<!-- ## 🔗 Additional Resources

- [Security Documentation](https://docs.adminbolt.com/security)
- [Hardening Guide](https://docs.adminbolt.com/security/hardening)
- [Compliance Guide](https://docs.adminbolt.com/security/compliance)
- [Audit Logs](https://docs.adminbolt.com/security/audit-logs)

--- -->

**Last Updated**: October 2025

