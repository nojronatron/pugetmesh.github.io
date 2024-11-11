---
status: new
---

# Meshtastic
<img src="media/MLA_Node.jpg" alt="Puget Mesh Node" width="750">

Meshtastic® is a project that lets you use inexpensive LoRa radios as a long range off-grid communicator for areas without reliable cellular service. These radios are great for hiking, skiing, paragliding - essentially any hobby where you don't have reliable internet access. Each member of the mesh can send and view text messages and enable optional GPS based location features.

The radios automatically create a mesh to forward packets as needed, so everyone in the group can receive messages from even the furthest member. The radios will optionally work with your phone, but no phone is required.


## Joining
Are you interested in joining the mesh? You will need to purchase a LoRa radio from the [Supported Hardware](https://meshtastic.org/docs/hardware/devices/) list which start at about $35. Outside of the mesh, we are most active on our public [Discord Server](https://discord.gg/ANvUg3AyZt).

### MQTT and Maps
Meshtastic devices can be connected to the internet and exchange information (messages, data, telemetry, etc) by using a MQTT server. The vast majority of us have chosen not to use MQTT with meshtastic in the spirit of embracing the RF mesh itself. However, we do utilize our own MQTT server for exchanging position data which is plotted on a map. This is helpful for understanding where the mesh needs to grow, and is helpful for onboarding new users.

There are a few public maps available showing nodes (that choose to share their position). We use [https://meshtastic.davekeogh.com/](https://meshtastic.davekeogh.com/) which currently looks something like this:
<img src="media/11Nov2024_MapSShot.png" alt="Dave Keogh Meshtastic Map" width="500">


## Best Practices
### TL;DR;
- **Role**: Client
- **Hop Count**: 3
- **Broadcast Intervals(info, position, telemitry)**: 3hours (10800 seconds)

[Configuration Recommendations](config)

## New User Expectations
It is important to know that Meshtastic is under rapid development, and is not yet a *polished* product. There are bugs and quirks but that is part of the fun. If you have just turned on your Meshtastic device for the first time, get it in a good location (being next to a window can help) and let it run overnight. It takes time to see other nodes, and for other nodes to see you, assuming you are somewhere with decent coverage. 

## Troubleshooting
- Is your device misbehaving?
- Are you struggling to get connected to the mesh (after letting your device run for 24 hours)?
- Have other questions or comments?
- [Austin Mesh](https://www.austinmesh.org/join/) is a good resource for Meshtastic information.

Come join our [Discord](https://discord.gg/ANvUg3AyZt)