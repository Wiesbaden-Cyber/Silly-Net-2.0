**Organization**: Wiesbaden STEM Lab Cyber  
**Effective Date**: October 2, 2024						**Revision Number**: 0

Purpose  
---

This document outlines the proper procedure to install, manage, and document Ethernet cables for Wiesbaden STEM Lab Cyber. Adhering to this policy will simplify troubleshooting.

Cable Color Code  
---

| Color | Use Case |
| :---- | :---- |
| White | Layer 2/3  (Routers, Switches, Firewalls) |
| Yellow | Wireless (APs/Controllers) |
| Blue | Endpoints (Desktops/Laptops) |
| Black | Management Network |
| Red | ISP Uplink |

Labeling Guide  
---

Adhere to [ANSI/TIA-606-B Labeling Standard](https://resources.duralabel.com/articles/ansi-tia-606-b-cable-labeling-standards). Use a label maker to create labels. If there is no label maker, then use a paper-slip and tape around it to create a flag. Cables must be labeled on both ends of the connection. In addition, place the label approximately 4 inches behind the cable connector. Provided below is a breakdown and short explanation of ANSI/TIA-606-B Labeling Standard: 

**1SR01-35:05/DC.A04-35:05** : near-end connection / far-end connection

**1SR01**: 1 indicates Floor, SR indicates STEM Lab Rack, 01 indicates cabinet number  
**\-35**: Indicates location of switch/patch panel in rack units in the cabinet  
**:05**: Indicates the port on the switch/patch panel 

**/**: Separates the near end from the far end connection

**DC.A04**: DC indicates DoDea Cabinet and that the cable is located in the 4th row of Row A  
**\-35**: Indicates location of switch/patch panel in rack units in the cabinet  
**:05**: Indicate port on the switch/patch panel

Explanation:  
The first section before the slash (**1SR01-35:05**) indicates the nearest end connection. The section after the slash (**DC.A04-35:05**) indicates the farthest end connection. To better clarify, if the cable was in the STEM Lab rack, then **1SR01-35:05** would be first since it is the closest end connection. The connection to the DoDea Cabinet (**DC.A04-35:05**) would be the far end connection since it is farthest from the STEM Lab rack. This label’s order would reverse on the side of the cable that’s in the DoDea Cabinet (i.e. **DC.A04-35:05/1SR01-35:05**). 

Below are the termination codes that are recognized by Wiesbaden STEM Lab Cyber.

| Termination Code | Termination Location |
| :---- | :---- |
| SR | STEM Lab Rack |
| DC | DoDea Cabinet |
| TC | Layer 2/3 devices |
| AP  | Access Point |
| EP | Endpoints |

Cable Management Guideline  
---

1) Ethernet cables of same color must be bunched together   
2) Ethernet cables must be bunched with velcro ties. If velcro ties are unavailable, then cable ties are permitted as a temporary solution.   
3) Ethernet cables must have approximately 6 inches of slack   
4) Ethernet cables with excessive slack must be neatly coiled until there is approximately 6 inches of slack 

