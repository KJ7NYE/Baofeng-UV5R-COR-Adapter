# Baofeng UV-5R COR Adapter Readme

**Credits:** This project is based on the work of WB4BXO. His original work can be found at: [https://github.com/wb4bxo/UV-5R-COS](https://github.com/wb4bxo/UV-5R-COS).

**Description:** This repository provides detailed information and schematics for a circuit designed to enhance the Baofeng UV-5R handheld transceiver. The circuit facilitates Carrier Operated Switch (COS) functionality without requiring any physical modifications to the radio. It enables seamless integration with various applications such as AllStar, packet radio, APRS, and others that necessitate a soundcard connection with COS. Additionally, it offers compatibility with an RC-210 repeater controller.

**Important Notes:**

- **Compatibility:** This circuit's operation is contingent upon the presence of approximately 3.3V DC offset on the headphone output when the Carrier Operated Relay (COR) is active. As this may vary between individual radios, it's advisable to conduct thorough testing to ascertain compatibility.
- **Activity Detection and Time Out:** This circuit does not include activity detection or a time-out timer. It is recommended to set the Time-Out Timer (TOT) of the attached radio to an appropriate value in case of prolonged transmission.
- **RF Interference:** Ensure that RF from the attached HT does not interfere with the Raspberry Pi (RPi) or other components. Take necessary precautions to prevent RF feedback.

- **License:** This project is licensed under the CERN Open Hardware License Version 2 - Permissive. Please refer to the license file for the full text of the license.
- **Disclaimer:** Please note that this circuit is provided as-is, and any modifications or implementations are done at your own risk. Ensure proper understanding of the circuit and its implications before usage.

For further details and support, refer to the documentation and feel free to reach out for assistance or inquiries.

**Author:** KJ7NYE
