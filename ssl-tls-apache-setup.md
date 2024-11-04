# SSL/TLS Configuration Project

**Project Overview**  
This project addresses an SSL certificate trust issue identified by a Nessus scan, leading to the setup of a self-signed SSL certificate on an Apache server.

**Steps Taken**:
1. **Generate Self-Signed Certificate**: Used OpenSSL to create a self-signed certificate.
2. **Configure Apache**: Modified Apache settings to use SSL and listen on port 443.
3. **Test the Setup**: Accessed `https://localhost` to verify HTTPS functionality.

**Screenshots**:
- **Nessus Scan Result**: ![Nessus SSL Trust Issue](Screenshot 2024-11-03 at 23.27.30.png)
- **OpenSSL Command**: ![Generating SSL Certificate](Screenshot 2024-11-04 at 04.49.41.png)
- **Apache Configuration**:
  - ![Apache SSL Configuration Part 1](Screenshot 2024-11-04 at 04.54.49.png) <!-- Replace with actual file name -->
  - ![Apache SSL Configuration Part 2](Screenshot 2024-11-04 at 04.55.12.png) <!-- Replace with actual file name -->
  - ![Apache SSL Configuration Part 3](Screenshot 2024-11-04 at 04.55.28.png) <!-- Replace with actual file name -->
  - ![Apache SSL Configuration Part 4](Screenshot 2024-11-04 at 04.55.45.png) <!-- Replace with actual file name -->
- **Test Result**: ![HTTPS Connection](Screenshot 2024-11-04 at 04.54.49.png)

**Outcome**: This configuration provides HTTPS encryption, although the self-signed certificate will show a browser warning.
