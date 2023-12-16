Typically targets NTLM. A technique whereby an attacker captures a password hash (as opposed to the password characters) and then passes it through for **authentication and lateral access**

# Pass the hash vs Pass the ticket

**Pass the ticket targets Kerberos**

The primary difference is **ticket expiration**. Kerberos TGT tickets expires whereas NTLM hashes only change when an user’s password changes

Best Defense → Enforce least privilege access, analyze applications to determine which require admin privileges, use flexible policies that allow only trusted applications to run and in specific context.

**Also “Credential Guard” in Windows 10 encrypts hash in memory, stopping this attack**
