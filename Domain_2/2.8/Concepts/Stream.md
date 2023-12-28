1. **Real-Time Encryption:**
    
    - Encrypts data bit by bit in real-time as it is transmitted.
2. **Efficiency:**
    
    - Well-suited for streaming applications due to their efficiency in processing continuous data flows.
3. **Key Stream Generation:**
    
    - Utilizes a key stream generator to produce a sequence of pseudorandom bits, combined with the plaintext using bitwise XOR.
4. **RC4 and ChaCha20:**
    
    - Common stream ciphers include RC4 and ChaCha20, each with unique strengths and considerations.
5. **Initialization Vector (IV):**
    
    - Requires a secure initialization vector to ensure unique encryption of each packet or message.
6. **Bitwise XOR Operation:**
    
    - Achieves encryption by combining the plaintext and the key stream using the bitwise XOR operation.
7. **Not Suitable for Random Access:**
    
    - Stream ciphers are not suitable for random access, as decryption depends on the order of bit processing.
8. **Security Considerations:**
    
    - The security of stream ciphers relies heavily on the unpredictability and strength of the key stream.