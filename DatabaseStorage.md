Database Storage

## Status

Proposed


# Context

This includes the specific details related to the project, application, or systems where the database will be used. It encompasses factors like the type of data being stored such as user profiles, game progress, and transaction records.  The scale of data whether it is small, moderate, or large datasets, data security requirements, the need for data synchronization across devices, and any relevant compliance regulations


# Decision

The combination of local storage, and encrypted storage for the payment details and user information. 


# Consequences

The consequences might include real-time data synchronization, the need for a stable internet connection, and the ability to scale the game to a larger user base. However, in local storage without encryption, the consequences might involve simpler development but potential security risks if the device is compromised.
