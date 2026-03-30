# A7. Discover cryptography used in modern networks

A type of cryptography commonly used in modern networks is **TLS (Transport Layer Security)**.

TLS is the security protocol that protects data as it travels between a user’s device and a website, for example, when logging into the **UWA student account** . When I open the login page in my browser, the site uses `https://` which mean it is secure, which means the connection is protected by TLS.

During the TLS connection, the browser and UWA’s server use **public‑key cryptography** to agree on a shared secret key, then use **symmetric encryption** to encrypt my username, password, and other data. This keeps my login details private and makes it much harder for attackers to steal my credentials, even if they can see the network traffic.
