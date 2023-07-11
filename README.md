# 📚✨ The Book of Ra ✨📚

Welcome to the **Book of Ra**, a magical collection of Ansible playbooks for automating your server setup and management tasks! 🧙‍♂️💻

## 🌈 Description 🌈

The **Book of Ra** is a treasure trove of Ansible playbooks designed to help you automate the setup and management of your servers. Each playbook in the Book of Ra is a chapter that covers a specific task, such as setting up a firewall, installing a VPN, or configuring SSH. By using these playbooks, you can quickly and easily set up your servers exactly the way you want them, without having to manually perform each step. 🚀

## 🎁 Features 🎁

The **Book of Ra** currently includes the following playbooks:

- **🔒 User Management 🔒**: This playbook sets up a new user with sudo privileges and applies various hardening measures to enhance user security. It allows you to specify the username, password, and a list of SSH key files for authentication.

- **🔐 Firewall Configuration 🔐**: This playbook configures the UFW firewall and applies essential rules to protect your server. It allows you to specify the firewall rules and ports to allow or block.

- **🔑 SSH Hardening 🔑**: This playbook applies advanced security measures to secure your SSH connection. It disables root login, sets maximum login attempts, configures login grace time, disables password authentication, and allows SSH access only from specific IP addresses.

- **🌐 WireGuard VPN Setup 🌐**: This playbook installs Docker, configures Docker to use ZFS, and runs a WireGuard VPN in a Docker container. It allows you to specify various settings for the VPN, such as the host, password, default address, and allowed IPs. It also configures UFW to allow the VPN ports.

With these modular playbooks, you have the freedom to choose and combine the specific configurations you need for your server setup, making the Book of Ra a versatile tool for automating your server management tasks. ✨💪

## 💡 Intended Usage

The 📘✨ **Book of Ra** playbooks are designed to simplify and automate server setup and management tasks across various environments. They can be utilized in different scenarios, including:

- 🖥️ **Physical Machines**: 🏢 The playbooks are suitable for automating server configuration and management on 💪 physical machines running Debian-based operating systems, such as Debian, Ubuntu, Linux Mint, Kali Linux, and others.

- 📦 **Virtual Machines**: 🌐 Whether you're using traditional virtualization platforms like VMware or modern cloud-based solutions like VirtualBox, the playbooks can be employed to automate the ⚙️ setup and management of your 🖥️ virtual machines running Debian-based operating systems.

- ☁️ **Cloud Instances**: ☁️ If you have SSH access to your ☁️ cloud instances or virtual machines running Debian-based operating systems, such as those provided by 🚀 AWS EC2, Azure VMs, Google Cloud Compute Engine, or DigitalOcean Droplets, you can utilize the playbooks to automate their 🎛️ configuration and management. Ensure that your cloud environment allows you to 📥 clone the Book of Ra repository to access the playbooks.

- 🚀 **Proxmox VE LXC Containers**: 📦 The playbooks have been specifically tested and optimized for use within 🏢 Proxmox VE LXC containers running Debian-based operating systems. They leverage the capabilities of Proxmox VE to create highly efficient and isolated environments.

The 🔀 flexibility and adaptability of the playbooks allow you to automate your server infrastructure across a range of environments, providing consistency, security, and ease of management.

## ⚙️ Requirements

To make use of the 📘✨ **Book of Ra** playbooks, you will need the following:

- 🐧 **Debian/Ubuntu-like System**: 🐧 The playbooks are compatible with a wide range of 🐧 Debian-based operating systems, including Debian, Ubuntu, Linux Mint, Kali Linux, and others.

- 💻 **Bash Environment**: 💻 The playbooks are designed to be run from a 💻 Bash environment, which is available on various platforms such as 🐧 Linux, macOS, Windows (using tools like Git Bash, Cygwin, or Windows Subsystem for Linux), and cloud-based development environments like AWS CloudShell, Google Cloud Shell, and Microsoft Azure Cloud Shell.

- 🗝️ **SSH Access (for Remote/Cloud Machines)**: 🔑 If you plan to use the playbooks for remote or cloud machines, ensure that you have 🔒 SSH access to those machines. This will allow Ansible to establish secure connections and perform the necessary configuration tasks. Additionally, make sure your cloud environment allows you to 📥 clone the Book of Ra repository to access the playbooks.

By meeting these 🎯 requirements, you can unlock the full potential of the **Book of Ra** playbooks and automate your server management tasks with 💫 ease and confidence. 🚀✨

## 🚀 Usage 🚀

To use the **Book of Ra**, simply download and run the `Open.sh` script. This script will update your system, install Ansible, and guide you through the process of selecting and running a playbook.

Here's how you can download and run the script:

```bash
wget https://raw.githubusercontent.com/LucianPetri/BookOfRa/main/open.sh
chmod +x open.sh
./open.sh
```

This will start the interactive script that guides you through the process. Just follow the prompts to select and run a playbook. 🧞‍♂️

## 🤝 Contributing 🤝

Thank you for considering contributing to the **Book of Ra**! We believe in the power of community collaboration and welcome your contributions to make this collection of playbooks even more comprehensive and powerful. Together, we can create a library of automation that covers a wide range of server setup and management tasks, empowering users to automate their workflows with ease. ✨💪

### 💡 How to Contribute

To contribute to the **Book of Ra**, follow these steps:

1. **🔱 Fork the Repository**: Start by forking this repository to your own GitHub account. This will create a copy of the repository under your account.

2. **🚀 Clone the Repository**: Clone the forked repository to your local machine. This will create a local copy that you can work with.

3. **🌟 Create a New Branch**: Create a new branch in the repository to work on your changes. Use a descriptive name that reflects the purpose of your contribution.

4. **✍️ Add Your Playbook**: Create a new playbook or improve an existing one. Each playbook should focus on a specific task and provide clear instructions for automation. Feel free to get creative and showcase your expertise!

5. **💾 Commit Your Changes**: Once you have made your changes, commit them to your branch. Provide clear and concise commit messages that describe the changes you have made.

6. **📤 Push to Your Forked Repository**: Push the changes to your forked repository on GitHub.

7. **🔀 Create a Pull Request**: Go to the original repository and create a pull request. Provide a detailed description of your changes, explaining the purpose and benefits of your playbook. Our team will review your contribution and provide feedback.

### 📋 Guidelines for Contributions

To ensure a smooth and collaborative experience, please follow these comprehensive guidelines when contributing to the **Book of Ra**:

- **🏗️ Playbook Structure**: Each playbook should have a clear and concise structure, with appropriate variables and tasks. Use comments to explain the purpose of each section and provide instructions where necessary. Aim for a modular design that promotes reusability and flexibility.

- **📖 Documentation**: Include comprehensive documentation within the playbook to guide users through the setup and usage. Clearly explain any prerequisites, variables, and configuration options. Provide examples and best practices for customizing the playbook to suit different environments.

- **🔧 Reusability**: Aim to create playbooks that are modular and reusable. This allows users to mix and match playbooks to suit their specific needs and create customized automation workflows. Consider creating separate roles or tasks for different functionalities, making it easier for users to integrate the playbooks into their existing setups.

- **🔒 Security and Best Practices**: Follow industry best practices for security, performance, and reliability in your playbooks. Implement secure configurations, such as strong authentication methods, encryption, and least privilege principles. Avoid hardcoding sensitive information and utilize Ansible's vault or other secure credential management methods. Regularly update and test the playbooks to ensure compatibility with the latest software versions.

- **🧪 Testing**: Thoroughly test your playbooks to ensure they work as intended. Write automated tests using Ansible's built-in testing framework or other testing tools. Test against different scenarios and edge cases to validate the playbook's reliability and compatibility. Document the testing process and provide instructions for users to verify the playbook's functionality.

- **🌟 Examples and Best Practices**: Provide examples and best practices within your playbooks. Share your knowledge and expertise to help users understand the recommended configurations and usage patterns. Include comments and explanations to clarify the reasoning behind specific choices and configurations.

- **📚 Documentation Standards**: Adhere to consistent documentation standards within the **Book of Ra**. Use clear and concise language, follow a consistent formatting style, and provide helpful references and external resources where applicable. Aim to make the documentation user-friendly and accessible to users of all skill levels.

- **🤝 Collaboration and Communication**: Foster a positive and collaborative environment within the **Book of Ra** community. Encourage open discussions, provide constructive feedback, and be respectful of others' contributions. Engage in meaningful conversations to enhance the quality and effectiveness of the playbooks.

Let's strive for excellence by embracing these guidelines and ensuring that the playbooks in the **Book of Ra** reflect the highest standards of automation and best practices. Together, we can create a comprehensive resource that empowers users to automate their server management tasks with confidence and ease! 🚀✨


## 🤝 Let's Collaborate!

We value your contributions and appreciate your commitment to making the **Book of Ra** a comprehensive resource for server automation. By contributing your playbooks, you help create a vibrant community that shares knowledge and empowers others to automate their server management tasks.

Join us in this exciting journey of automation and contribute to the **Book of Ra** today! Together, we can unlock the true power of Ansible and simplify server management for everyone. 🚀✨🤖


## 📜 License 📜

### The **Book of Ra** is enchanted with the power of open-source magic and is licensed under the  🪄✨ **GPL V3.0 License** ✨🪄.

This means that you are free to use, modify, and distribute the playbooks in the Book of Ra. You can even create your own magical variations and share them with others! However, please note that any modifications or additions you make to the Book of Ra must also be released under the same GPL V3.0 License.

We believe in the spirit of collaboration and the magic of open-source, where knowledge is shared and freely available to all. Let's continue the enchantment and keep the magic alive by respecting the terms of the GPL V3.0 License.

For more details about the GPL V3.0 License, please see the [LICENSE](LICENSE) file in this repository.

✨🌟 May the magic of the Book of Ra guide you on your automation journey! 🌟✨
