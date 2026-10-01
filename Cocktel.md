<p align="center">
  <img src="https://img.shields.io/badge/EN-English-cccccc?style=for-the-badge" alt="English (current)">
  <a href="Cocktel.de-DE.md"><img src="https://img.shields.io/badge/DE-Deutsch-dd9900?style=for-the-badge" alt="German"></a>
</p>

# proDAD Cocktel: The Pioneering Software for Live Video Telephony over Analog Telephone Lines

With *Cocktel*, proDAD developed a technically spectacular software system in 1997 that was years ahead of its time. Long before broadband Internet, video conferencing platforms, or smartphones became part of everyday life, *Cocktel* enabled the synchronous transmission of live video and audio over ordinary analog telephone lines. The software impressively demonstrated the potential of the Amiga platform in the areas of real-time data compression and digital communication.

---

## *Cocktel v1* (1997)

* **Software developer:** Holger Burkarth
* **Manufacturer:** proDAD GmbH
* **Platform:** Exclusively for Amiga
* **Product category:** Real-time video telephony & audio/video communication software

### Description & Technical Innovations
The biggest hurdle in developing *Cocktel* was the extremely low bandwidth of analog telephone networks at the time. Standard modems achieved transfer rates of only 28.8 to 33.6 kbit/s in 1997. Over this narrow bottleneck, video images and voice signals had to be transmitted simultaneously and without disruptive latency.

Because no off-the-shelf software components existed for this challenge, proDAD founder Holger Burkarth developed custom, highly optimized compression algorithms:

* **Intelligent differential video compression:** Instead of transmitting complete individual frames, *Cocktel* analyzed the video frames on the main processor and transmitted only the pixel areas that changed from frame to frame. This drastically reduced the data volume to just a few kilobytes per second.
* **Real-time audio quantization & lip synchronization (lip sync):** In parallel with the video image, the analog voice signal was captured via a digitizer, heavily compressed, and routed synchronously with the video stream over the same modem interface.
* **Direct hardware control:** *Cocktel* captured the video signal from a connected camera directly, processed it on the Amiga main processor, and passed the data packets directly to the modem's serial interface.

---

## Technological Background & System History

Although *Cocktel* was celebrated in expert circles as an algorithmic masterpiece, the product never achieved commercial breakthrough. The system suffered from a classic network effect: in 1997, the private sector lacked both broad acceptance and nationwide hardware infrastructure (modems and camera digitizers) for video telephony.

Only about six years later (starting in 2003) did the concept of video telephony on the Windows PC experience its worldwide triumph with the arrival of broadband Internet (DSL) and providers such as Skype. Nevertheless, *Cocktel* remains impressive proof of proDAD's pioneering spirit and its ability to create functioning real-time systems even under extreme hardware restrictions.

---

## Main Features & Unique Selling Points at a Glance

* **Technological pioneering effect:** First working live video telephony software for the Amiga over analog telephone lines.
* **Extremely efficient algorithms:** Synchronous transmission of image and sound over modems with only 28.8–33.6 kbit/s bandwidth.
* **Intelligent differential compression:** Minimization of data volumes by transmitting only image changes.
* **Real-time hardware processing:** Direct capture from audio/video digitizers and live output via the serial interface.


## Links
- [Home](README.md)
- [All Products](ProductTimeline.md)