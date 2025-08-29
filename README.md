# 🚀 WATCH-CPU-FREQUENCY-REALTIME 🚀

![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)
![GitHub stars](https://img.shields.io/github/stars/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME.svg?style=social)
![GitHub forks](https://img.shields.io/github/forks/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME.svg?style=social)
![GitHub issues](https://img.shields.io/github/issues/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME)
![Made with Bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)

A simple yet powerful Bash script to monitor your CPU core frequencies in real-time, right from your terminal.

![demo](https://user-images.githubusercontent.com/86934450/193433333-317f8185-1793-4e30-b283-849557764b8e.png)

---

## ✨ Features

-   **Real-time Monitoring**: Watches CPU frequency for all cores every half-second.
-   **Lightweight**: Minimalist script with no heavy overhead.
-   **Dependency-Aware**: Automatically checks for and attempts to install missing dependencies on Debian-based systems.
-   **Simple & Clean**: Uses standard Linux commands (`watch`, `grep`) for maximum compatibility.

## 🖥️ Compatibility

This script is designed to be highly compatible with most Linux distributions. It is confirmed to work on:

!Debian
!Ubuntu
!Linux Mint

...and other Debian/Ubuntu derivatives that use the `apt` package manager.

For other distributions (e.g., Fedora, Arch), the script will work perfectly as long as the dependencies are installed manually.

## 🛠️ Dependencies

The script requires the following tools to be present on your system:

-   `grep` (standard on almost all Linux systems)
-   `procps` (which provides the `watch` command)

If you are on a Debian-based system, the script will automatically try to install `procps` using `sudo apt-get` if the `watch` command is not found. You may be prompted for your password.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME.git
    cd WATCH-CPU-FREQUENCY-REALTIME
    ```

2.  **Make the script executable:**
    ```sh
    chmod +x custom-WATCH-CPU-FREQUENCY-REALTIME.sh
    ```

3.  **Run the script:**
    ```sh
    ./custom-WATCH-CPU-FREQUENCY-REALTIME.sh
    ```

Press `Ctrl+C` to stop the monitor.

## 💬 Contributing

[Pull requests](https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME/pulls), [issues](https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME/issues), and [suggestions](https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME/issues/new/choose) are warmly welcomed!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 🌐 Links

-   [Issues](https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME/issues)
-   [Pull Requests](https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME/pulls)
-   [Releases](https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME/releases)
-   [Wiki](https://github.com/LINUX-OASIS/WATCH-CPU-FREQUENCY-REALTIME/wiki)

## 🧙‍♂️ Maintainer

-   **[LINUX-OASIS](https://github.com/LINUX-OASIS)**

## 📜 License

This project is licensed under the **GNU General Public License v3.0**. See the `LICENSE` file for details.
