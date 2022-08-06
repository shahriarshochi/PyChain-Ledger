# PyChain-Ledger

This project focuses on building a blockchain-based ledger system, completed with a user-friendly web interface.This ledger should allow banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Methods and Techniques Used:

The steps that I took for this project can be devided into 4 sections for better understanding

### 1.  Creating a Record Data Class:

Firstly I will be defining a new Python data class named Record. Then I will be giving this new class a formalized data structure that consists of attributes named sender and receiver of type str and the amount attribute of type float.  I will be using this new Record class as the data type of my record attribute in the next part.

### 2. Modifying the Existing Block Data Class to Store Record Data:

In this portion I will rename the data attribute in my Block class to record, and then I will set it to use an instance of the new Record class that I created in the previous section.

### 3. Adding Relevant User Inputs to the Streamlit Interface:

Next I will be coding additional input areas for the user interface of my Streamlit application. Then I will be creating the input areas to capture the sender, receiver, and amount from the user for each transaction that will be stored in the Block record.

### 4. Test the PyChain Ledger by Storing Records:

The final step is to test the completed PyChain ledger and user interface by running the Streamlit application and storing some mined blocks in the PyChain ledger. Then test the blockchain validation process by using the PyChain ledger. We will be needing to navigate to the folder where the python file for this project is, and then with our terminal, we will be launching the streamlit app. As coded we will see a dataframe, sender receiver and amount section and ofcourse an add block button to add blocks to the dataframe and verifying the whole transaction.


## Goal of This Project:

The goal of this project is to allow banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger quickly, efficienty and leaving the traditional methods of banking which would take hours or days behind with the help of blockchain technology.


