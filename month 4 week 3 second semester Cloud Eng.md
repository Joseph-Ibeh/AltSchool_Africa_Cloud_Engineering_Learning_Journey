# 🚀 Cloud Engineering Journey Update! 🚀

Last week at AltSchool Africa, in the Cloud Engineering program, I immersed myself in foundational cloud engineering skills, focusing on file permissions, ownership, and secure remote connections—essential for anyone managing cloud resources!

## 🔐 File Permissions & Ownership with `chown` and `chmod`

I learned how to control file access using `chown` and `chmod`, two essential tools for setting who can read, write, or execute a file. Here’s a bit of what I covered:

### Detailed Permissions with `chmod`
We explored the `chmod` command and its numerical values (e.g., 755, 644) as well as symbolic forms (e.g., `rwx` for read, write, execute). These configurations help structure access by users, groups, and others, ensuring files are managed securely.

- Numerical Representation:
  - `755`: Owner can read, write, execute; group can read, execute; others can read, execute.
  - `644`: Owner can read, write; group can read; others can read.
  
Understanding these permissions is crucial for protecting sensitive files and ensuring that only authorized users have access.

### Assigning Ownership with `chown`
I also worked with `chown` to assign ownership of files and directories, enabling more control over who can access specific resources. Verifying permissions and ownership with `ls -l` was another crucial step, giving me a solid understanding of access details.

- Example Command: `chown user:group filename` 
  - This command changes the ownership of the specified file to the designated user and group, enhancing security by limiting access to specific individuals.

## 💻 Ubuntu Installation on EC2

An important step last week was installing Ubuntu on Amazon EC2 and launching my own cloud instance! 🌐 This gave me hands-on experience in deploying virtual machines and setting up my environment on the cloud, including handling SSH configurations for secure access.

- EC2 Overview: Amazon EC2 (Elastic Compute Cloud) provides scalable computing capacity in the cloud, allowing users to launch and manage server instances with ease.

## 🔑 SSH and Key Pairs

I explored SSH (Secure Shell) for secure remote access, using an AWS-generated key pair for authentication. After downloading the private key file, I used it directly on my terminal to securely connect to my EC2 instance. 

- Key Pair Usage: A key pair consists of a public key and a private key, with the public key stored on the server and the private key kept secure on the client machine. This method provides a secure way to log in without the need for passwords.

- SSH Command: `ssh -i path/to/private-key.pem ubuntu@your-ec2-ip`
  - This command allows for encrypted access to the EC2 instance, enhancing security and preventing unauthorized access.

Diving into these concepts has sharpened my skills and boosted my confidence in cloud management. Each new lesson gets me one step closer to my goal of becoming a cloud engineer, and I can’t wait to keep pushing forward and building even more! 🚀
![practical](https://github.com/Joseph-Ibeh/AltSchool_learning_journey/blob/main/images/first%20instance.jpg)
![practical](https://github.com/Joseph-Ibeh/AltSchool_learning_journey/blob/main/images/sshing%20into%20%20my%20first%20instance%20from%20my%20CLI.jpg)
