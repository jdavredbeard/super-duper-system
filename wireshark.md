1. Yes there was a DNS query made (when using incognito mode in the browser). The TTL value was 300 (5 minutes).
2. The window size of the SYN/ACK response is 65535
3. The server selected cipher suite TLS_AES_128_GCM_SHA256 - using Protocol: Transport Layer Security, Encryption: Advanced Encryption Standard with 128bit key in Galois/Counter mode, and Hash: Secure Hash Algorithm 256. This cipher suite does not specify Key Agreement or Authetication elements - those are negotiated elsewhere in the handshake.