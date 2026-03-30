# A8. Discover cryptography used in Internet of Things devices

A type of cryptography commonly used in Internet of Things devices is **symmetric encryption such as AES (Advanced Encryption Standard)**.

IoT devices like smart lights, smart locks, and sensors often need to send data over the internet for example, temperature readings or door‑lock status. To protect this data, the device encrypts it using a secret key before sending it to a home hub or cloud server. AES turns the original data into scrambled, unreadable text so that only the device and the server that share the key can read it no ones else in the world can read it.

This helps protect privacy and security because even if an attacker intercepts the network traffic, they cannot understand the real data without the key. Many IoT products use AES‑128 or similar lightweight encryption because it is strong enough for security but still efficient for small devices with limited processing power. **Because we don't want everyone in the world can access your door.**
