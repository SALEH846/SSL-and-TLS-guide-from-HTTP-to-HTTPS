### Certificates
- The most important information stored by any certificate is the public key of the owner of the certificate.
- Every entity in PKI has its own public key.
- It's a digital entity -- a file with some data
- Important info that a certificate holds:
    - Information about owner
    - Information about issuer
    - Signature
    - Public key
- If a certificate is signed by CA, and we trust that CA then it means we also trust the owner of that certificate too.
- Self-signed certificate: A certificate is issued and signed itself by the owner
- Public key in the certificate belongs to the owner, not to the issuer