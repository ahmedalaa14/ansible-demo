# Ansible Playbook for Web Server Configuration

- This playbook is specifically designed for configuring web servers on Ubuntu machines. It's a part of our effort to automate and standardize our server setup process.

## 🚀 Features

- **Web Server Configuration**: Sets up a web server on the host machine, saving you the time and effort of manual configuration.
- **Secure Operations**: Prompts for a password during execution for secure operations, ensuring that only authorized users can make changes.

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed [Ansible](https://www.ansible.com/) on the control node.
- You have SSH access to the host machine.
- The host machine is running Ubuntu OS.

## 🏃‍♂️ Usage

Follow these steps to use this playbook:

1. Clone this repository to your local machine using `git clone`.
2. Navigate to the directory containing the playbook.
3. Run the playbook using the following command:

```bash
ansible-playbook web.yaml
```

- You will be prompted to enter a password during execution.

## 📚 Roles

- The playbook uses the following roles:

- web: This role is responsible for configuring the web server.
## 🤝 Contributing
 - Please feel free to submit a pull request or create an issue for any enhancements.