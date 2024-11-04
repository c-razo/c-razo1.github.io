# SSL/TLS Configuration Project

**Project Overview**  
This project addresses an SSL certificate trust issue identified by a Nessus scan, leading to the setup of a self-signed SSL certificate on an Apache server.

**Steps Taken**:
1. **Generate Self-Signed Certificate**: Used OpenSSL to create a self-signed certificate.
2. **Configure Apache**: Modified Apache settings to use SSL and listen on port 443.
3. **Test the Setup**: Accessed `https://localhost` to verify HTTPS functionality.

**Screenshots**:
- **Nessus Scan Result**: ![Nessus SSL Trust Issue](Screenshot 2024-11-03 at 23.27.30.png)
- **OpenSSL Command**: ![Generating SSL Certificate](path/to/your/screenshot2.png)
- **Apache Configuration**: ![Apache SSL Configuration](path/to/your/screenshot3.png)
- **Test Result**: ![HTTPS Connection](path/to/your/screenshot4.png)

**Outcome**: This configuration provides HTTPS encryption, although the self-signed certificate will show a browser warning.
