# Quantum Voice Secure

## Overview

Quantum Voice Secure is an experimental project that aims to provide secure real-time voice communication with quantum-safe encryption. In an era where data security is of paramount importance, this project combines cutting-edge technologies to ensure the confidentiality and integrity of your voice messages.

The project consists of several key components, including:

1. **Audio-to-Text Conversion:** It starts with an audio message that is transformed into text using the Whisper API in Python. This allows users to communicate using both voice and text seamlessly.

2. **Quantum Key Distribution:** Quantum security is at the heart of this project. We implement the BB84 quantum key distribution algorithm using the Qiskit library to establish a secure key between the sender and receiver.

3. **Encryption:** Once a secure quantum key is established, the Advanced Encryption Standard (AES) algorithm is employed to encrypt the text message. AES is a well-established encryption standard, and by using a quantum-safe key, we ensure that the encrypted message remains secure against future quantum attacks.

4. **Decryption:** On the receiver's side, the message is decrypted using the same quantum-safe key and AES decryption, guaranteeing the confidentiality of the message.

5. **Text-to-Audio Conversion:** The decrypted text is converted back into an audio message using the QTTS API in Python. This provides an added layer of privacy and security, ensuring that the receiver hears a synthesized voice, preserving the sender's identity and enhancing the overall safety of communication.

## Project Goals

The primary goal of this project is to showcase a proof of concept for real-time voice calls with quantum-safe shared keys. As quantum computers advance, traditional encryption methods may become vulnerable, and quantum-safe encryption is essential to protect sensitive communications. Quantum Voice Secure demonstrates that it's possible to integrate these emerging technologies into a practical, user-friendly communication system.

## How to Use

The project code is available in this repository, and we provide detailed documentation on how to set up and run Quantum Voice Secure. You'll need the necessary APIs (Whisper and QTTS) and libraries (Qiskit) to get started. Follow the instructions in the documentation to set up the environment, establish a secure key, and initiate secure voice communication.

## Contributing

We welcome contributions from the open-source community to help enhance the project. Whether you have ideas for additional features, want to improve security measures, or simply want to fix bugs, please consider contributing to Quantum Voice Secure. We encourage you to follow these guidelines when contributing:

1. Ensure that your contributions are in compliance with the project's licensing terms. Quantum Voice Secure is released under the [Creative Commons Attribution-NonCommercial License 4.0](LICENSE), which means that any contributions must also adhere to these non-commercial terms.

2. Please note that this project is intended for non-commercial and educational use. We do not accept contributions that may be used for commercial purposes without prior consent.

By contributing to Quantum Voice Secure, you agree to abide by these terms, fostering a community of collaboration that aligns with our project's licensing objectives. If you have any questions or suggestions, please feel free to reach out to us.

---

## License

This project is released under the [Creative Commons Attribution-NonCommercial License 4.0](LICENSE). This license restricts the use of the project for commercial purposes. You are free to use, modify, and distribute the project for non-commercial and educational purposes. If you wish to use this project for commercial purposes, please contact the project owner for appropriate licensing.

---
