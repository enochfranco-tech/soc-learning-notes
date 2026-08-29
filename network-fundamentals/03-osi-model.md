## What is the OSI Model?

The OSI Model breaks down network communication into seven layers. These layers are useful for identifying network issues.

## 7. Application Layer —
This layer itself is not the app; it uses the services and rules of the application layer. For example, say I want to send a message that I want to do an internship working with Albert Einstein, so I send a message on WhatsApp. Now Albert Einstein will see the message on his laptop using a browser. The browser uses the rules and services (protocols) of the application layer. This is why it's called the application layer.

Common Application Layer Protocols:

HTTP / HTTPS → Web browsing and data transfer
SMTP → Sending emails
IMAP / POP3 → Receiving emails
FTP → File transfer between client and server
DNS → Resolving domain names into IP addresses
Telnet / SSH → Remote login and command execution
SNMP → Network device monitoring and management
NTP → Synchronizing clocks across systems

## 6. Presentation Layer —
This is the layer responsible for sending and receiving the message (data). I'll explain it simply: the presentation layer is responsible for the translation, encryption, and compression of data. Continuing my internship example, I sent a picture on WhatsApp of the projects I'd done to Albert Einstein. Here, the presentation layer compressed the data before sending it to Layer 5. This helps improve the speed and efficiency of communication by minimizing the amount of data that needs to be transferred.

## 5. Session Layer —
Now Albert Einstein accepted my request to work with him as an intern. He said, "First, buy and read my course." So I bought the course using a QR code sent by Albert Einstein.

Stepwise Breakdown (QR Code Use):

You scan a QR code.
The QR code contains some data (like a link, text, or payment info). This is Application Layer (Layer 7) work — it interprets the QR content.
Session Layer role: When your device connects to the server behind that QR code (say, a website or app), the session layer establishes and manages the communication session. It ensures:
Your device and the server know they're "talking" to each other.
The session stays active until the task (like opening the site or confirming data) is complete.
If you leave or time out, the session closes.
Why it matters: Without the session layer, scanning the QR code would just send raw data, with no guarantee of a stable "conversation" with the server. The session layer keeps track of the interaction, so your QR scan leads to a proper, secure exchange.
This is called the session layer.

## 4. Transport Layer —
In simple terms, the transport layer carries data by segmenting it (breaking the data into chunks) and delivering it safely (end-to-end communication) to Layer 3. On the receiver's side, the transport layer reassembles the segments.

Sender side: The transport layer chops big data into smaller segments.
Receiver side: The transport layer collects those segments and rebuilds them into the original message.
The transport layer uses two protocols: Transmission Control Protocol (TCP) and User Datagram Protocol (UDP).

## 3. Network Layer —
Now that I've bought and completed the course, I want to tell Albert Einstein that I've finished it, so I send the message "Sir Albert Einstein, I have completed the course you sent. Can I now join as an intern to work with you?" on WhatsApp. I'll use this message to explain the network layer.
The message I sent is the data. The network layer is used to send data from one network to another. It breaks segments (which consist of data) from the transport layer into smaller units called packets and sends them to the data link layer. If the receiver is on the same network, this step isn't needed.
The network layer also finds the best physical path for the data to reach its destination; this is known as routing. The network layer uses protocols such as IP, Internet Control Message Protocol (ICMP), Internet Group Management Protocol (IGMP), and the IPsec suite.

## 2. Data Link Layer —
In the network layer, packets (data) are sent from one network to another, but in the data link layer, the packets are broken into frames and sent within a single network.

## 1. Physical Layer —
This layer deals with the actual hardware used for data transmission, such as cables and switches. It is also responsible for turning data into a stream of bits — sequences of 1s and 0s. Both devices must follow the same signaling rules so that each side can correctly recognize which signals represent 1s and which represent 0s.

## So, that's the OSI Model — and the good news is, I got the internship to work with Albert Einstein!
