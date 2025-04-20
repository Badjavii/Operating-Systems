# Definition of an Operating System

Defining what an operating system is can be challenging. This concept has evolved over time. However, we can identify two main functions of an operating system:

## Function 1 - The Operating System as an Extended (or Virtual) Machine

When we refer to an extended (or virtual) machine, we mean a specialized working environment for the user.

The default working environment of a computer is primitive and very user-unfriendly. It involves low-level operations such as:
- Configuring disk reads
- Handling interrupts
- Managing incidents
- Any other type of physical component manipulation

This primitive environment was inefficient, which led to the decision to hide it through software. This software that conceals the hardware's reality is the operating system. Thus, **the first function** is to provide the user with an abstraction layer to create a more comfortable environment.

This function presents an operating system concept that follows a **bottom-up** perspective.

## Function 2 - The Operating System as a Resource Manager

An alternative perspective, **top-down**, defines that the operating system has the function of controlling physical components. It provides orderly and controlled hardware allocations for various software.

The operating system can bring order to potential chaos. Chaos might manifest as:
- Resource shortages
- Overload from too many programs running simultaneously
- Device access conflicts

### Practical Example:
Imagine a user sends multiple documents to print simultaneously on the same printer. We know that:
- Printers typically can only process one sheet at a time
- If we attempt to print multiple documents simultaneously, we would get:
    - Sheets with mixed fragments of different documents
    - No complete documents
    - Unintelligible results
    - A chaotic process

The operating system solves this problem by:
1. Organizing print requests
2. Processing them one by one
3. Maintaining order even though the user sent all documents simultaneously

Previously, users had to wait for one document to finish printing before sending the next. Now, the operating system handles this management automatically.