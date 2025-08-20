# Blockchain Ride-Sharing Simulation in Python

A beginner-friendly simulation of a decentralized ride-sharing system using Python.
This project demonstrates the core concepts of blockchain, smart contracts, tamper detection, and transaction flow without using an actual blockchain — perfect for understanding the logic behind Uber-like decentralized apps

# Features

✅ Request ride with rider name, fare, and payment method

✅ Multiple payment modes: Crypto, UPI, Cash, Digital

✅ Rider wallet address required only for Crypto

✅ Smart contract simulation with:
      
      Rider & driver assignment
      
      Fare & payment method recording
      
      Ride status transitions


✅ Tampering detection using SHA-256 hashing

✅ Ride cannot be completed if data is altered

✅ Clean terminal interface for user input & output

✅ Role-based access: Only driver can complete ride


# How It Works

Rider initiates a ride by choosing a payment method, fare, and (optionally) wallet address.

The system logs all ride details and computes a cryptographic hash (like a smart contract log).

The driver confirms payment to complete the ride.

Before completion, the system verifies that no one tampered with the ride data (fare, status, etc.).

If the hash is different, tampering is detected and the ride fails.


# Concepts Used

Smart contract simulation using Python classes

Data immutability check via SHA-256 hashing

Conditional logic for role & payment rules

CLI interaction for user and driver roles

Secure transaction flow (with detection for manipulation)
