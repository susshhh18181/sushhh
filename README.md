SimpleTimeCapsule Contract
A simple Solidity smart contract that allows the owner to store a message in a "time capsule" and retrieve it only after a specified unlock time.

Overview
The SimpleTimeCapsule contract allows the owner to:

Set an unlock time: The owner can specify a future time after which the stored message will be accessible.
Store a message: The owner can store a message in the contract.
Retrieve the message: The owner can retrieve the message once the unlock time has passed.
This contract utilizes basic time-based conditions and ensures that only the owner of the contract can interact with it.

Features
Owner-only access: Only the owner can store and retrieve the message.
Unlock time: The message can only be retrieved after a specified unlock time, ensuring time-based control.
Prevents overwriting: Once a message is stored, it cannot be overwritten.
 DEPLOYED ADDRESS- 0x1834e411f497d87a78b83fEFE1555B52C60c3800
