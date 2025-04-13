## grief.ac
#### Minecraft's [Grim](https://grim.ac) for Scratch.
Developed by [sweup](https://scratch.mit.edu/projects/1134516648/)

Grief (stylized as *grief*), is a packet-based state machine simulation anticheat for Scratch platformers, boasting a 97.16% engine accuracy rate (13 attack vectors) with 0 false flags and 0 bypasses (as of 13/04/2025).

You can find the latest version at https://scratch.mit.edu/projects/1134516648/.

#### Overview
Grief uses Minecraft-inspired packets in order to communicate with the client, and runs on the server-side (Scratch emulated). This allows it to be exceptionally modular, only requiring modifications to the prediction checks (hosted in a single thread) in order to work on other styles of platformer-type games.

As Grief is a packet anticheat, it is realistic in regards to TCP, UDP, WS and alike protocols, and would work perfectly on them (including latency and compensation), which makes it unique to other Scratch anticheats.

#### Contributing
You can fork Grief and do whatever you like with it. sweup provides first-hand support to anyone that wants to learn about Grief, packet anticheats, bypassing, or the alike.

There are a few guidelines to using Grief for yourself:
- You may not distribute or use any of Grief's code without clearly linking to it.
- You may not claim Grief as your own in any way.
- You may not copy a single check. If you are going to use Grief's code alongside other code, you must make it clear what is Grief.

*List of Grief forks*
Name | Developer | Version | Forked | Features | Link
---- | --------- | ------- | ------ | -------- | ----
warden.ac | [Sparky](https://scratch.mit.edu/users/rahiamthebest/) | b1 | b6 | Highly improved prediction accuracy | [Link](https://scratch.mit.edu/projects/1161124468/)

Those wanting to bypass Grief are also highly appreciated contributors.
