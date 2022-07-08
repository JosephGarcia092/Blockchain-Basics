# Pychain-Ledger

## Create a Record Data Class
- Create a Data class _record_ to store basic information about the Transaction such as  
    - Sender
    - Receiver
    - Amount
- Create a **Block** class to store data from _User_ 
- Take Record Data class to be passed throught the **Block** data class for Recording
- Make sure to keep track of the _TimeStamp, ID, Previous Hash, and Nonce_
- Defined a function to **Encode** stored data with __SHA 265 encryption__ from the _Block class_ with having the ability to update as the user inputs more information/Data.


## Making a Chain

Took the newly made and encoded _Block_ and passed said _Block_ through the next step of having it attached to a class defined as **Pychain** or _Chain_.
Along with setting the difficulty for _Hashing_, I took the _Block_, sent it through both a _Proof of Work and Validation_ function to verify if the **Hash** is _Valid and Correct_ by means of the **Proof of Work Consensus** followed by a _is_Valid_ function to have previous hash confirm the _hash_ matches to be put on the _Blockchain_. I allowed a _Print_ statment to show the user that the _Blockchain is a Valid chain_.

### Streamlit 

Streamlit was used here for a Webapp to be User friendly. To show the User a way to see the Ledger of the Blockchain from what _sender_ who the _receiver_ was and the _amount_ of the transaction. 
Create a slide bar to increase the difficulty of the _hash_ for the chain. Also, made the interface more dynamic to see a specific block with a verification button to validate the Block. 

