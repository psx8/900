# PSFree 9.00 - PlayStation Pulse Edition

A stable WebKit exploit chain for PlayStation 4 firmware 9.00, featuring the PSFree exploit combined with the Lapse kernel exploit for homebrew execution.

## Overview

PSFree is a WebKit exploit that leverages CVE-2022-22620 to achieve arbitrary read/write capabilities on PS4 consoles. This implementation specifically targets firmware 9.00 and includes performance optimizations for improved stability and execution speed.

**Key Features:**
- 🎯 **Firmware Support**: PS4 9.00 (93% stability rate)
- ⚡ **Fast Execution**: Optimized exploit chain with performance tweaks
- 🔗 **Kernel Access**: Integrated Lapse kernel exploit for full system access
- 📱 **Web-based**: Runs directly in the PS4 browser - no additional tools required
- 💾 **Offline Cache**: Built-in caching system for reliable offline usage

## How It Works

1. **WebKit Exploitation**: Uses a SerializedScriptValue use-after-free vulnerability to gain memory read/write
2. **Kernel Exploitation**: Chains with the Lapse kernel exploit to escalate privileges
3. **Payload Execution**: Enables homebrew and unsigned code execution

## Usage

Simply navigate to the hosted page on your PS4 9.00 console's web browser. The exploit will automatically cache itself for offline use and execute the payload chain.

## Compatibility

- **PlayStation 4**: Firmware 9.00
- **Stability**: ~93% success rate
- **Requirements**: PS4 web browser only

## Credits

- **abc** - Original PSFree WebKit exploit & Lapse kernel exploit
- **kameleonre** - Porting and chaining PSFree + Lapse for PS4 9.00
- **SiSTR0, CTN, Al-Azif, Chendochap** - Additional contributions and research
- **Jhon** - Development support

---

**Author**: [BlackArch](https://t.me/sudoBlackArch)  
**Community**: [PlayStation Pulse](https://t.me/PlayStation_Pulse)

*This project is for educational and research purposes. Use responsibly.*
