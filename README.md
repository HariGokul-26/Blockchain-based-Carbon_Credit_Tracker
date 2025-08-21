# Blockchain-based-Carbon_Credit_Tracker
🌱 Blockchain Carbon Credit Tracker in Python

A beginner-friendly simulation of a green blockchain system for tracking carbon credits.
This project demonstrates the core concepts of blockchain, smart contracts, tamper detection, and transaction flow — perfect for understanding how companies trade & use carbon credits in a transparent way.


---

🚀 Features

✅ Issue carbon credits for companies (earned from green projects)
✅ Use credits to offset emissions
✅ Prevent double-spending of credits
✅ Immutable ledger using SHA-256 hashing
✅ Full transaction history (who earned/used, when, why)
✅ Tamper detection: no one can alter credits after recording
✅ Balance check for each company
✅ Simple CLI interface for easy testing


---

⚙️ How It Works

1. A company earns credits when it invests in green initiatives (e.g., planting trees, solar farms).


2. Credits are stored on a blockchain ledger with timestamp + hash.


3. When the company offsets emissions, credits are deducted.


4. The system checks:

✅ Does the company have enough balance?

✅ Has any record been tampered with?

✅ Is the ledger still valid?



5. If tampering or overspending occurs → the transaction is rejected.




---

📖 Concepts Used

Smart contract simulation via Python classes

Blockchain structure: blocks with hash, prev_hash, timestamp

Data immutability using SHA-256 hashing

Double spending prevention by credit balance checks

Audit trail: full history of credit issuance & usage

CLI interaction for companies to earn/use credits



---

🖥️ Demo Flow (Example)

1. 🌍 EcoAir Ltd earns 1200 credits from a wind farm project.


2. ✈️ Uses 300 credits to offset August flights.


3. ☀️ Earns 500 credits from a solar PPA.


4. 🚢 Uses 900 credits for cargo operations.


5. ❌ Attempts to use 700 credits while only 500 available → rejected.


6. Blockchain verifies integrity → ledger is valid & tamper-free.
