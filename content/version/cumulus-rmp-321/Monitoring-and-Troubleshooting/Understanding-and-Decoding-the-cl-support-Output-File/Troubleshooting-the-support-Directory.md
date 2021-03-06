---
title: Troubleshooting the support Directory
author: Cumulus Networks
weight: 185
aliases:
 - /display/RMP321/Troubleshooting+the+support+Directory
 - /pages/viewpage.action?pageId=5127569
pageID: 5127569
---
The `support` directory is unique in the fact that it presents the
output from several commands, rather than being a copy of the switch's
filesystem. For example:

| File            | Equivalent Command               | Description                                                                                                                  |
| --------------- | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| support/ip.addr | `cumulus@switch:~$ ip addr show` | This shows you all the interfaces (including swp front panel ports), IP address information, admin state and physical state. |

