OSI Model
What is the OSI Model?

The OSI (Open Systems Interconnection) model is a conceptual framework that helps us understand how devices communicate over a network.

It divides network communication into 7 layers.

The 7 OSI Layers
Application – Provides network services to applications used by people.
Presentation – Handles data formatting, encryption, and compression.
Session – Establishes, manages, and terminates communication sessions.
Transport – Provides end-to-end communication and controls how data is delivered. Examples include TCP and UDP.
Network – Handles logical addressing and routing. IP operates here.
Data Link – Handles frames, MAC addresses, and communication between devices on the same local network. Ethernet operates here.
Physical – Transmits raw bits through cables, fiber, radio waves, or other physical media.
Easy Way to Remember

From Layer 7 down to Layer 1:

Application → Presentation → Session → Transport → Network → Data Link → Physical

A simple memory aid is:

All People Seem To Need Data Processing

Why the OSI Model Matters

The OSI model helps us understand what happens to data as it travels from one device to another. It also helps network engineers troubleshoot problems by identifying which layer may be responsible for an issue.

Example

When a computer sends data to another computer:

The application creates the data.
The transport layer prepares it for delivery.
The network layer adds logical addressing such as IP addresses.
The data link layer prepares a frame using MAC addresses.
The physical layer sends the data as bits across the network medium.

At the destination, the process happens in reverse. The receiving device removes the information added by each layer until the original data reaches the application.
