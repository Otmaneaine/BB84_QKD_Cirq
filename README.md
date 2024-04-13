# Quantum Key Distribution (QKD) using BB84 Protocol

## Overview
This Python script demonstrates Quantum Key Distribution (QKD) using the BB84 protocol to establish a secure key between Alice and Bob. The generated key is then used to encrypt and decrypt a message using classical XOR encryption.

## Dependencies
- Python 3.9.0 or greater.
- Cirq: Google's Python library for creating, simulating, and optimizing quantum circuits


## Setup

### Running Locally with Jupyter Notebook
1. Clone or download the repository to your local machine.
2. Make sure you have Python 3.9.0 or greater installed.
3. Install the required dependencies by running:
    ```
    pip install cirq
    ```
4. Open Jupyter Notebook by running the following command in your terminal or command prompt:
    ```
    jupyter notebook
    ```
5. Navigate to the directory containing the downloaded files and open the provided Jupyter Notebook.
6. Run the notebook cells sequentially by clicking on "Run" -> "Run All Cells".

### Running on Google Colab
1. Open Google Colab (https://colab.research.google.com/).
2. Click on "File" -> "Upload notebook" and upload the provided Jupyter Notebook.
3. Run the notebook cells sequentially by clicking on "Runtime" -> "Run all".

Note: For running on Google Colab, you don't need to install any dependencies as Colab comes pre-installed with Cirq.


## Usage
1. The code generates a random message and converts it into binary representation.
2. Alice and Bob perform the BB84 protocol to establish a shared key.
3. The shared key is used to encrypt the message using classical XOR encryption.
4. Bob decrypts the encrypted message using the shared key.
5. Verify if the decrypted message matches the original message.

## Code Explanation
- The code begins by importing necessary libraries including Cirq and defining the message to be encrypted and decrypted.
- The message is encoded into binary representation using UTF-8 encoding.
- Quantum Key Distribution (QKD) is performed between Alice and Bob using the BB84 protocol.
- The generated shared key is used to encrypt and decrypt the message using classical XOR encryption.
- Finally, the script verifies if the decrypted message matches the original message.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
