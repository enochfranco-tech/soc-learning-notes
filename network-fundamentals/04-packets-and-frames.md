## What is Packets and Frames?
A packet is a piece of data from Layer 3 (Network Layer) of the OSI model, containing information such as an IP header and payload. A frame, however, is used at Layer 2 (Data Link) of the OSI model, which, encapsulates the packet and adds additional information such as MAC addresses.

## What is TCP/IP?
TCP (Transmission Control Protocol): Ensures data is delivered reliably, in order, and error‑free.
IP (Internet Protocol): Handles addressing and routing, making sure data goes to the right destination.
Together, TCP/IP is the standard communication language of the internet.

Real-Life Examples -

WhatsApp Message: When you send “Hi” to a friend, TCP/IP ensures the message arrives correctly, even if your mobile signal drops for a second.

YouTube Streaming: TCP/IP ensures video packets arrive in the right order, so you don’t see scrambled frames.

## The 3-Way Handshake -
Before sending data, TCP does a “handshake” to confirm both sides are ready:

SYN (Client → Server):  
Your phone says: “Hello server, I want to talk. Here’s my starting number.”

SYN + ACK (Server → Client):  
The server replies: “Got it! Here’s my number too. Ready?”

ACK (Client → Server):  
Your phone confirms: “Okay, I received your number. Let’s start!”

After this, the connection is ESTABLISHED and data flows smoothly.

## What is UDP/IP?
UDP (User Datagram Protocol): A lightweight way of sending data.
It doesn’t check if the data arrived correctly or in order.
IP (Internet Protocol): Same as before—it handles addressing and routing.
So, UDP/IP = Fast delivery, but no guarantee.

Real-Life Examples -

YouTube Live / Twitch Streaming: Video packets are sent quickly. If one packet is lost, the stream continues (better to skip a frame than pause).

Online Gaming (PUBG, Free Fire): Position updates are sent rapidly. If one update is lost, the next one fixes it—speed matters more than perfection.

Voice Calls (WhatsApp, Zoom): If one word drops, the conversation continues. Better to keep talking than wait for missing data.
