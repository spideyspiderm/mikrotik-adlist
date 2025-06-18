# MikroTik AdList

A curated collection of DNS blocklists specifically formatted for MikroTik RouterOS DNS filtering functionality.

[![Update DNS Filters](https://github.com/IgorKha/mikrotik-adlist/actions/workflows/update-filters.yaml/badge.svg)](https://github.com/IgorKha/mikrotik-adlist/actions/workflows/update-filters.yaml)

## Overview

This project automatically generates and maintains DNS blocklists in the proper format for [MikroTik RouterOS DNS AdList feature](https://help.mikrotik.com/docs/spaces/ROS/pages/37748767/DNS#DNS-adlistAdlist). The lists are designed to block ads, trackers, malware, and other unwanted content at the network level.

## Features

-   **Auto-generated lists**: Automatically sourced from trusted filter repositories
-   **MikroTik-ready format**: Pre-formatted for direct use with RouterOS DNS settings
-   **Regular updates**: Lists are refreshed automatically every 7 days
-   **Multiple categories**: Various blocklists for different filtering needs
-   **Reliable sources**: Based on community-maintained and verified filter lists

## Data Sources

All blocklists are automatically generated from the **AdGuard Host Lists Registry**:

-   **Registry URL**: https://adguardteam.github.io/HostlistsRegistry/assets/filters.json
-   **Repository**: https://github.com/AdguardTeam/HostlistsRegistry
-   **Update frequency**: Weekly (every 7 days)

The AdGuard Host Lists Registry maintains a comprehensive collection of DNS filtering lists from various sources, ensuring high-quality and up-to-date blocking rules.

## Usage

1. Browse the available blocklists in the `hosts/` directory
2. Choose the appropriate list for your filtering needs
3. Configure your MikroTik router to use the selected list URL
4. The lists will be automatically updated as your router fetches them

### MikroTik Configuration

For detailed configuration instructions, please refer to the official MikroTik documentation:

-   **DNS AdList Configuration**: https://help.mikrotik.com/docs/spaces/ROS/pages/37748767/DNS#DNS-adlistAdlist

> [!IMPORTANT]
> When using large blocklists, consider increasing the DNS cache size to ensure sufficient memory for storing blocked domains. This can be configured in the DNS settings to prevent performance issues.
> **DNS cache-size configuration**: https://help.mikrotik.com/docs/spaces/ROS/pages/37748767/DNS#DNS-DNSconfiguration

The official documentation provides up-to-date configuration examples and troubleshooting information for RouterOS DNS filtering features.

## Available Lists

Check the `hosts/` directory for currently available blocklists. Each list is named according to its source and purpose, making it easy to select the right one for your needs.

## Automation

This project runs automated updates to ensure:

-   Fresh blocklist data every week
-   Proper formatting for MikroTik compatibility
-   Removal of duplicates and invalid entries
-   Consistent file structure and naming

## License

This project (transformation scripts, automation, and documentation) is licensed under the MIT License.

The transformed blocklists are derived from various upstream sources, each with their own licensing terms. While the transformation and formatting are provided under MIT license, the original filter data remains subject to their respective source licenses. Users should review individual source licenses if redistribution or commercial use is intended.

![visitors](https://visitor-badge.laobi.icu/badge?page_id=igorkha.mikrotik-adlist)
