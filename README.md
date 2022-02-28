# PracaInzynierska
## Principles:
1. Text based communicator with extended data transfer options:
    - Sending files
    - Sending and natively viewing images
    - Markdown support
    - End-To-End Encryption of messages?
    - Message group support
2. Backend:
    - Storage for user login data and messages log
    - Messages should be encrypted and viewable only for users
    - No personal data unless needed for necessary identity verification should be stored persistently
---
## Implementation:
1. Frontend:
    - Mobile application written in Kotlin/C#(Xamarin)
    - Simple, intuitive UI
2. Backend:
    - C#/Python based (not sure yet)
    - Storage implemented in some NoSQL database (MongoDB?) or maybe Entity Framework with SQL database in case of C#
3. General:
    - All communication should be done via secure http requests- this will require some playing with asymmetric encryptions, keys and possibly certificates.
