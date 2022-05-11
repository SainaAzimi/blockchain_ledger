# **Blockchain Ledger using Streamlit**
The pychain builds a blockchain-based ledger system, complete with a user-friendly web interface. This ledger allows partner banks to conduct financial transactions and to verify the integrity of the data in the ledger.

---

## Technologies
This application is developed on the *Python 3.7.11 version*:

**Pandas**: A software library that allows to import functions needed to program appliation for financial analysis.

**streamlit**: A software that allows for deploying data apps.

**dataclasses**: A software that allows for decorator and functions for automatically adding generated special methods such as init() and repr() to user-defined classes.

**typing**: A software that allows for runtime support for type hints.

**datetime**: A software that allows for manipulating dates and times.

**hashlib**: A software that allows for common interface to many different secure hash and message digest algorithms.

---

## Installation Guide
Before running the application first install the following:
```
- pip install streamlit  

- pip install pandas
```

---

## Usage
Initially, the PyChain app creates a class for Records, whose attributes include Sender, Receiver, and Amount. The user inputs values for each of these attributes through the Streamlit UI.

In order to use the application, run the comman '''streamlit run pychain.py''' in the terminal, this opens the homepage of the app:
![photo_1](Resources/photo_1.png)

In the application you create transactions that are saved in the ledger at the bottom as well as validate the chain:
![photo_2](Resources/photo_2.png)

---

## Contributors

*Contributors*: Saina Azimi

*Email*: azimi.sainaa@gmail.com

*LinkedIn*: https://www.linkedin.com/in/azimi-saina/ 

---

## License
UC Berkeley

---