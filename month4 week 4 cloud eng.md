# 🌟 Exciting Learning Journey at AltSchool Africa - Cloud Engineering 🚀

Last week was an intensive hands-on learning experience as I continued my Cloud Engineering journey at AltSchool Africa!

## Hands-on Learning with CLI

I focused on practical learning using the Command Line Interface (CLI) in my local setup, which is essential for efficiently managing servers and performing tasks in cloud environments.

### User and Group Management

- Dynamic Group Creation: I created three dynamic groups: Admin, Support, and Engineering. 
  - Example: To create the `Admin` group, I used the command:
    ```bash
    sudo groupadd Admin
    ```
  - This helps in organizing users based on their roles and responsibilities within the system.

- Adding Admin Group to Sudoers: I added the Admin group to the sudoers list, granting elevated privileges to its members!
  - Example: By editing the `/etc/sudoers` file with `visudo`, I added the line:
    ```bash
    %Admin ALL=(ALL:ALL) ALL
    ```
  - This configuration allows users in the Admin group to execute commands with root-level access, which is crucial for administrative tasks.

- User Creation: I created a user in each of the groups to understand role-based access better.
  - Example: To create a user named `alice` in the Admin group, I used:
    ```bash
    sudo useradd -m -G Admin alice
    ```
  - Similarly, I created users `bob` in the Support group and `charlie` in the Engineering group:
    ```bash
    sudo useradd -m -G Support bob
    sudo useradd -m -G Engineering charlie
    ```
  - This practice establishes clear access control and management based on user roles.

### SSH Key Generation

I generated SSH keys for the user in the Admin group, solidifying my grasp of secure remote access.
- Example: For the `alice` user, I generated SSH keys using the command:
  ``bash
  sudo -u alice ssh-keygen -t rsa -b 2048

  ![Groups](https://github.com/Joseph-Ibeh/AltSchool_learning_journey/blob/main/images/creating%20group.jpg)
