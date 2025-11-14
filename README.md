# Python Projects 
This repository is designed to highlight my progress as I incorporate learning Python into my daily routine. Below is a list of projects and their general descriptions that I have completed so far.

## Getting Started 💻
### Prerequisites
You only need __Python 3__ installed on your system.

__How to Run a Project__
1. __Clone the repository__ (or download the files).
2. Navigate to the project's directory (e.g., ``cd luhn-algorithm/``).
3. Execute the Python file from your terminal:
   ``Bash python luhn_algorithm.py``

## 🛡️ Project Algorithms 
### Caesar Cipher ``caesar-cipher/`` :
* Originating from Roman times, this cipher encrypts data by shifting each letter a fixed number of places (e.g., 3 letters for the original Caesar shift). Our implementation ensures case preservation and correctly handles the alphabetical wrap-around.
### Vigenere Cipher ``vigenere-cipher/``:
* An extension of the Caesar cipher, it uses a repeating keyword to apply different offsets to each letter, making it significantly harder to break than the single-shift Caesar cipher.
### Luhn Algorithm ``luhn-algorithm/``:
* Designed to validate credit card numbers by checking if the formatting follows a specific pattern, which helps prevent accidental input errors.

## Future Goals💡
* Implement the Luhn algorithm with a graphical user interface (GUI) 
* Add a test suite for each cipher using Python's ``unittest`` module
* Explore more complex classical ciphers (e.g., Hill Cipher). 
