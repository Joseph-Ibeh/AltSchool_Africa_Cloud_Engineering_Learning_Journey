## Last Week at AltSchool Africa Cloud Engineering Program

### Networking Fundamentals: IP Addresses, Binary, Netmask, and Classification

Last week, I had the opportunity to dive into some key networking concepts as part of my studies at the AltSchool Africa Cloud Engineering Program. Here’s a summary of what I learned: 

### IP Addresses
An IP (Internet Protocol) address is a unique identifier assigned to devices on a network, enabling them to communicate with each other. There are two versions of IP addresses:

- IPv4 (Internet Protocol version 4): A 32-bit address scheme, providing around 4.3 billion unique addresses.
- IPv6 (Internet Protocol version 6): A 128-bit address scheme, which vastly expands the number of available unique addresses.

### Binary in Understanding IP Addresses
IP addresses are often represented in binary format to facilitate routing and subnetting. Each segment of an IPv4 address (e.g., `192.168.0.1`) is converted into 8-bit binary numbers. For example:

- `192` in binary is `11000000`
- `168` in binary is `10101000`
- `0` in binary is `00000000`
- `1` in binary is `00000001`

This binary representation is essential for understanding the network and host components of an address.

### Netmask
A netmask defines which portion of an IP address refers to the network and which part refers to the host. It works together with the IP address to segregate the network portion from the host portion.

- Typically represented in the same format as an IP address (e.g., `255.255.255.0`).
- The netmask uses `1` bits to represent the network portion and `0` bits for the host portion.

### Netmask Calculation
To calculate the netmask for a network, follow these steps:

1. Convert the IP address and netmask to binary.
2. Perform a bitwise AND operation between the IP address and the netmask to get the network address.
3. The result shows the network portion of the IP address.

Example:
- IP Address: `192.168.0.1` (binary: `11000000.10101000.00000000.00000001`)
- Netmask: `255.255.255.0` (binary: `11111111.11111111.11111111.00000000`)
- Network Address: `192.168.0.0`

### Classification of IP Addresses
IP addresses are categorized based on their usage and range. The primary classes include:

- Class A: IP addresses from `1.0.0.0` to `127.255.255.255`. Used for large networks.
- Class B: IP addresses from `128.0.0.0` to `191.255.255.255`. Used for medium-sized networks.
- Class C: IP addresses from `192.0.0.0` to `223.255.255.255`. Used for smaller networks.
- Class D: IP addresses from `224.0.0.0` to `239.255.255.255`. Used for multicast groups.
- Class E: IP addresses from `240.0.0.0` to `255.255.255.255`. Reserved for experimental use.

### Conclusion
This week’s lessons on IP addresses, binary conversion, netmask calculations, and classification of IP addresses have provided me with crucial networking knowledge. These fundamentals will be essential for future topics in cloud engineering and networking, laying the groundwork for more advanced cloud infrastructure concepts.
