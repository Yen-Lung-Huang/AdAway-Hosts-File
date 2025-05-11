# AdAway-Hosts-File

A comprehensive hosts file designed to block unwanted and harmful content, with a focus on blocking NSFW content.

## Overview

This project provides a collection of hosts files that can be used with AdAway, Pi-hole, or any other hosts-based blocking tool to prevent access to unwanted websites. The main focus is on blocking NSFW content, but it also blocks various ads and tracking services.

## Features

- Block NSFW content websites
- Block NSFW ads and trackers
- Optimized for mobile and desktop devices
- Regular updates to maintain effectiveness
- Organized in separate lists for better control

## Repository Structure

- `block_list/`: Contains hosts files for blocking unwanted content
  - `nsfw_hosts.txt`: Main hosts file for blocking NSFW websites
- `allow_list/`: Contains lists of domains to whitelist
  - `safe_ads.txt`: Non-intrusive ads that can be safely whitelisted

## Usage

### With AdAway (Android)

1. Open AdAway app
2. Go to "Hosts Sources"
3. Add the raw URL of the `nsfw_hosts.txt` file
4. Update and apply

### With Pi-hole

1. Log in to your Pi-hole admin console
2. Go to "Adlists"
3. Add the raw URL of the `nsfw_hosts.txt` file
4. Update your gravity database

### Manual Installation

You can manually copy the content of the hosts files to your system's hosts file:

- Windows: `C:\Windows\System32\drivers\etc\hosts`
- macOS/Linux: `/etc/hosts`

## Credits and Acknowledgements

This project builds upon and consolidates the excellent work done by:

- [Anti-Porn-HOSTS-File](https://github.com/4skinSkywalker/Anti-Porn-HOSTS-File) by 4skinSkywalker - A comprehensive collection of hosts for blocking NSFW content.
- [PornAway](https://github.com/mhxion/pornaway) by mhxion - An Android application that uses hosts file modifications to block NSFW websites.

Special thanks to these projects' maintainers and contributors for their pioneering work in creating and maintaining comprehensive lists of hosts files for content blocking.

## Contributing

Contributions are welcome! If you have suggestions, additions, or corrections, please:

1. Fork the repository
2. Create a new branch for your feature
3. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This hosts file is provided "as is" without any guarantees or warranty. The authors are not responsible for any damages or issues that may occur from using these host files. Users should use these lists at their own risk.
