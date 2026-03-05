NetCopy: Secure Network File Transfer

A network utility system written in **Python** for transferring files securely using TCP Sockets and MD5 integrity verification.

Components
- **Checksum Server:** Manages file IDs and their MD5 hashes with expiration times.
- **NetCopy Client:** Computes MD5, sends file data, and registers the checksum.
- **NetCopy Server:** Receives files and verifies their integrity.

Skills Demonstrated
- Network Programming (Socket API).
- Multi-threading in Python.
- Data Integrity & Hashing (MD5).

Usage
1. Start the `checksum_srv.py`.
2. Start the `netcopy_srv.py` to listen for incoming files.
3. Run `netcopy_cli.py` to send the file and verify its checksum.
