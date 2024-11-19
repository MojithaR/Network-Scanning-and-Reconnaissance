# Network Scanning Tools Installation Guide

## ![Install GIF](https://media.giphy.com/media/84ihvocszznNK/giphy.gif?cid=ecf05e472ct6bmamwzdsoio1y8j0s1xdteycr8uc5re00nxc&ep=v1_gifs_search&rid=giphy.gif&ct=g)

This guide will help you install the following network scanning and reconnaissance tools on **Windows**, **Mac**, and **Linux**:

- Nmap
- Nikto
- The Harvester
- Maltego
- Angry IP Scanner

---

## Installing on Windows and Mac

### Nmap

#### Windows
To install **Nmap** on Windows:
1. Download the installer from [Nmap's official website](https://nmap.org/download.html).
2. Run the installer and follow the on-screen instructions.

#### Mac
To install **Nmap** on Mac:
1. Install Homebrew (if not already installed) by running the following in your terminal:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Once Homebrew is installed, run the following command to install Nmap:
   ```bash
   brew install nmap
   ```

---

### Nikto

#### Windows
To install **Nikto** on Windows:
1. Download the latest version from [Nikto's GitHub page](https://github.com/sullo/nikto).
2. Extract the files and navigate to the folder using the terminal.
3. Run Nikto with Perl:
   ```bash
   perl nikto.pl
   ```

#### Mac
To install **Nikto** on Mac using Homebrew:
```bash
brew install nikto
```

---

### The Harvester

#### Windows
To install **The Harvester** on Windows:
1. Clone the repository:
   ```bash
   git clone https://github.com/laramies/theHarvester.git
   ```
2. Navigate to the directory and run the script using Python:
   ```bash
   python3 theHarvester.py -d <domain_name>
   ```

#### Mac
To install **The Harvester** on Mac using Homebrew:
```bash
brew install theharvester
```

---

### Maltego

#### Windows
To install **Maltego** on Windows:
1. Download the installer from [Maltego's official website](https://www.paterva.com/web7/).
2. Run the installer and follow the on-screen instructions.

#### Mac
To install **Maltego** on Mac:
1. Download the Mac version from [Maltego's website](https://www.paterva.com/web7/).
2. Run the installer.

---

### Angry IP Scanner

#### Windows
To install **Angry IP Scanner** on Windows:
1. Download the installer from [Angry IP Scanner's official page](https://angryip.org/download/#windows).
2. Run the installer and follow the on-screen instructions.

#### Mac
To install **Angry IP Scanner** on Mac:
1. Download the dmg file from [Angry IP Scanner's official page](https://angryip.org/download/#macos).
2. Drag the application to the Applications folder.

---

## Installing on Linux

To install the tools on Linux, use the following commands:

### Nmap
```bash
sudo apt update && sudo apt install nmap
```

### Nikto
```bash
sudo apt update && sudo apt install nikto
```

### The Harvester
```bash
sudo apt update && sudo apt install theharvester
```

### Maltego
Maltego does not have direct package support for Linux. To install it:
1. Download it from [Maltego's official page](https://www.paterva.com/web7/).
2. Follow the installation instructions provided on the website.

### Angry IP Scanner
```bash
sudo apt update && sudo apt install ipscan
```

---

## Just writing
This guide helps you get started with essential network scanning tools. Be sure to follow the installation steps carefully to set up the tools correctly on your system.
```
