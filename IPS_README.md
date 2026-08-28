# IPS — IP Location Lookup Tool

**Owner:** HARI  
**Tool Name:** IPS  
**Platform:** Termux / Bash  
**Version:** 2.0

## 📌 About IPS

**IPS** is a lightweight, colorful IP lookup utility designed for Termux.

It uses the public `ip-api.com` endpoint to display available IP-based network and approximate geographic information.

> **Important:** IP geolocation is approximate. An IP address does not reveal a person's exact GPS location or reliably identify their phone/device model.

## ✨ Features

- 🌍 Country
- 🗺️ Region
- 🏙️ City
- 📮 ZIP code
- 🕐 Timezone
- 🌐 ISP
- 🏢 Organization
- 🔢 ASN
- 📍 Approximate latitude and longitude
- 🎨 Colorful terminal interface
- 🖥️ Termux/Bash support
- 🚀 Simple one-command execution

## 📦 Requirements

Install Termux packages:

```bash
pkg update
pkg install curl python
```

## 🚀 Installation

Clone or download this repository, then enter its directory:

```bash
cd IPS
```

Make the script executable:

```bash
chmod +x location.sh
```

Run:

```bash
./location.sh
```

You can also run it with:

```bash
bash location.sh
```

## 🔎 Usage

Start the tool:

```bash
./location.sh
```

When prompted, enter an IP address:

```text
IP > 8.8.8.8
```

The tool will display the available location and network information.

## 📊 Example Output

```text
╔════════════════════════════════════════════════════╗
║                  IP INFORMATION                   ║
╠════════════════════════════════════════════════════╣
║ IP Address    : 8.8.8.8                           ║
║ Continent     : North America                     ║
║ Country       : United States                      ║
║ Country Code  : US                                 ║
║ Region        : ...                                ║
║ City          : ...                                ║
║ ZIP Code      : ...                                ║
║ Timezone      : ...                                ║
║ ISP           : Google LLC                         ║
║ Organization  : Google                             ║
║ ASN           : ...                                ║
║ Latitude      : ...                                ║
║ Longitude     : ...                                ║
║ Device Model  : Not available from IP              ║
╚════════════════════════════════════════════════════╝
```

## ⚠️ Accuracy & Privacy

IPS reports information returned by the IP geolocation service. The result can represent the network's registered or estimated location rather than the physical location of a particular person.

IPS does **not** provide:

- Exact GPS tracking
- Hidden/live device location
- A person's private browsing history
- Reliable remote phone model identification

Use the tool only for IP addresses and systems you are authorized to investigate.

## 🌐 API

IPS uses the free IP lookup endpoint from:

**ip-api.com**

The free endpoint is intended for non-commercial use and is subject to the provider's current rate limits and terms.

## 👤 Owner

**HARI**

## 📄 License

This project is provided for educational and authorized network-information lookup purposes.

Use responsibly and follow the API provider's terms of service and applicable laws.
