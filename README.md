# 🎧 Jungle Jams Tram: Enriching Zoo Encounter through RFID Audio

An **Arduino-based interactive audio system** designed to enhance zoo visits using RFID technology. As the tram moves past animal enclosures, RFID cards trigger pre-recorded audio tracks with information about the animals, offering visitors an immersive and educational experience.

## 🚀 Project Overview

**Jungle Jams Tram** integrates:
- 📻 RFID RC522 module
- 🎶 DFPlayer Mini MP3 module
- 🎛 Arduino Uno R3
- 🔊 8Ω 3W speaker

With strategically placed RFID tags across zoo tram checkpoints, the system automatically plays specific audio files when a tag is scanned—turning a tram ride into an engaging audio tour.

## 🧠 Problem Statement

Traditional zoo visits often involve:
- Limited visitor interaction
- Information overload on signage
- Underutilized technology

This project solves these problems by combining RFID with audio playback for dynamic, tailored content delivery.

## 🎯 Objectives

- Develop an automated RFID-triggered audio system
- Enhance visitor learning and enjoyment
- Promote wildlife conservation education

## 🔌 Circuit Diagram

![Circuit Diagram](images/circuit_diagram.png)

The circuit consists of several components such as:

| Component         | Description                     |
|------------------|---------------------------------|
| Arduino Uno R3   | Main microcontroller            |
| RFID RC522       | Scans RFID tags at exhibits     |
| DFPlayer Mini    | Plays audio files from SD card  |
| Speaker (8Ω 3W)  | Delivers audio to visitors      |
| 9V Battery       | Portable power source           |

## 📜 Features

- 🔄 Real-time RFID card scanning
- 🔊 Location-based audio playback
- 🧠 Curated educational content
- 📈 Scalable for more tram stops/exhibits

## 📷 Prototype Image

![Prototype of Jungle Jams Tram](images/prototype.png)

The RFID reader is installed underneath the tram. As the tram moves along the track, it passes over RFID cards embedded on the road at each animal habitat. When a card is detected, the system plays a specific audio clip through the onboard speaker to provide visitors with engaging information about the animals.


## 🔧 How It Works

1. RFID cards are placed at tram checkpoints.
2. The RFID reader on the tram detects the tag.
3. Arduino reads the UID and determines which audio file to play.
4. DFPlayer Mini plays the corresponding `.mp3` from the SD card.
5. The speaker outputs the audio to the visitors.
## 💻 Software & Tools

- **Arduino IDE** – for coding
- **Proteus** – simulation and testing
- **Altium Designer** – PCB layout
- **Fritzing** – circuit design visualization

## 🌍 Related SDGs

- **SDG 4: Quality Education**
- **SDG 13: Climate Action**
- **SDG 15: Life on Land**

## 👨‍💻 Contributors

- [Muhammad Zikry bin Zaharudin](#)
- [Muhammad Fahmi Hafizi bin Rosmidi](#)
- [Mohamad Firdaus bin Hasan](#)

> Supervised by: **Dr. Zaiton binti Abdul Mutalip**
