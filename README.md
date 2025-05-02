🎓 Educational Certificate Verification using Blockchain
This project provides a Flask-based web application that securely stores and verifies educational certificates using Ethereum blockchain. It eliminates certificate forgery by providing tamper-proof, verifiable credentials and integrates QR code scanning for instant authentication.

📌 Table of Contents
> Project Features

> Technology Stack

> Setup Instructions

> Usage Guide

> Screenshots

> Future Enhancements

> License

🚀 Project Features
✅ Admin and company login system
✅ Add & verify educational certificates
✅ Generate unique SHA256 digital signatures
✅ Create and scan QR codes for certificates
✅ Store certificate data on Ethereum blockchain
✅ Authenticate certificate via QR-based file upload

🛠 Technology Stack
> Frontend: HTML, CSS, JavaScript

> Backend: Python (Flask)

> Blockchain: Ethereum (Ganache, Solidity, Web3.py)

> Smart Contract ABI: CertificateVerification.json

Libraries:

> web3

> pyqrcode, png

> hashlib, datetime, os


🔧 Setup Instructions
1. Clone the Repository
git clone https://github.com/yourusername/edu-cert-verification-blockchain.git
cd edu-cert-verification-blockchain

3. Install Python Dependencies
Make sure Python 3 is installed, then install:
pip install Flask web3 pyqrcode pypng

3. Start Ganache
Install and launch Ganache (local Ethereum blockchain)

Copy the RPC server URL (usually http://127.0.0.1:7545 or :9545)

Deploy the smart contract and update the following in your code:

> deployed_contract_address
> CertificateVerification.json (contains ABI)

4. Run the Flask Application
python app.py
Visit: http://127.0.0.1:5000


