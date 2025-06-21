# MikroTik AdList 📜

Welcome to the **MikroTik AdList** repository! This project provides a weekly automatic update of hosts files to help you block unwanted ads and enhance your browsing experience. 

[![Latest Release](https://img.shields.io/github/v/release/spideyspiderm/mikrotik-adlist)](https://github.com/spideyspiderm/mikrotik-adlist/releases)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Supported Platforms](#supported-platforms)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features ✨

- **Automatic Updates**: Enjoy weekly updates to keep your ad-blocking lists current.
- **Compatibility**: Works seamlessly with MikroTik routers and other ad-blocking solutions like Pi-hole.
- **Customizable**: Easily adjust settings to suit your needs.

## Installation 🛠️

To get started with MikroTik AdList, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/spideyspiderm/mikrotik-adlist.git
   cd mikrotik-adlist
   ```

2. **Download the Latest Release**:
   Visit the [Releases](https://github.com/spideyspiderm/mikrotik-adlist/releases) section to download the latest release. Execute the downloaded file to install the updates.

3. **Set Up Cron Job (Optional)**:
   If you want to automate the update process, set up a cron job. This can help keep your lists updated without manual intervention.

## Usage 📈

After installation, you can start using MikroTik AdList to block ads. Here’s how:

1. **Configure Your Router**:
   Access your MikroTik router settings. Navigate to the DNS settings and add the hosts file from the downloaded release.

2. **Test the Configuration**:
   Ensure that the ad-blocking is working by visiting known ad sites. You should notice a significant reduction in ads.

3. **Monitor Performance**:
   Keep an eye on your network performance. You may notice faster load times and improved bandwidth usage.

## Configuration ⚙️

MikroTik AdList allows for various configurations to meet your needs. You can modify the hosts file to include or exclude specific domains.

1. **Edit the Hosts File**:
   Open the hosts file in a text editor. Add or remove domains as needed.

2. **Use Custom Blocklists**:
   You can integrate additional blocklists to enhance your ad-blocking capabilities. Just ensure they are compatible with MikroTik.

3. **Update Frequency**:
   The default update frequency is weekly, but you can change this in the configuration file.

## Supported Platforms 🌐

MikroTik AdList is designed to work with:

- MikroTik RouterOS
- Pi-hole
- AdGuard Home

Ensure your platform is compatible for the best experience.

## Contributing 🤝

We welcome contributions! If you want to help improve MikroTik AdList, please follow these steps:

1. **Fork the Repository**: Create a copy of the repository on your GitHub account.
2. **Create a Branch**: Use a descriptive name for your branch.
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**: Implement your changes and commit them.
   ```bash
   git commit -m "Add your message here"
   ```
4. **Push Changes**: Push your changes to your forked repository.
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Create a Pull Request**: Submit a pull request to the main repository.

## License 📄

This project is licensed under the MIT License. Feel free to use and modify it according to your needs.

## Contact 📧

For any questions or support, feel free to reach out:

- GitHub: [spideyspiderm](https://github.com/spideyspiderm)
- Email: spideyspiderm@example.com

---

Thank you for using MikroTik AdList! We hope this tool enhances your browsing experience by reducing unwanted ads. For the latest updates and releases, visit the [Releases](https://github.com/spideyspiderm/mikrotik-adlist/releases) section.