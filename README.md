#SSL certificate generation step by step
Configuration of Certification Authority AcmeCA with AcmeRootCA as the RootCA.
Configuration of the Web Server with Apache2 on a Linux Host. 
DNS configuration for www.verysecureserver.com
Firewall configuration to allow necessary ports (53, 80, 443) only
CSR Configuration and Generation for the www.verysecureserver.com
Transfering the CSR to AcmeCA.
Certification process (Verification and Certificate Generation from CSR)
Transferring the certificate from AcmeCA to www.verysecureserver.com
Installation of the signed the SSL certificate in the server of www.verysecureserver.com
Making the system trust Acme-RootCA
Implementation of a simple file uploading page in the server. 
Verifying the security of the connection by inspection (the padlock icon), and with wireshark from another computer. 
Revoke the certificate issued to www.verysecureserver.com from the CA and distribute the first CRL.
Verifying the revocation of previous certificate from the CRL (no padlock icon).
Configuring IDS.

