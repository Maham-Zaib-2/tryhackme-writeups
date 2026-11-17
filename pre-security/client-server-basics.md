# Client-Server Basics

**Path:** Pre Security
**Platform:** TryHackMe

## Goal
Understand how computers communicate and provide services to each other, using pizza delivery as the example.

## What I did
1. Learned the basic ideas: client, server, service, request, response, and protocol.
2. Learned what ports, DNS, and IP addresses are.
3. Got an overview of HTTP and its basic methods, then looked closely at the GET method.
4. Opened a web page, used Inspect, and went to the Network tab.
5. Reloaded the page to see the GET requests.
6. Examined one request to see the scheme, host, filename, address, and status.
7. Looked at the response body that came back.

## What I learned
- A client asks for something (a request) and a server sends it back (a response).
- A protocol is the set of rules both sides follow so they understand each other.
- An IP address is where a computer is, DNS turns website names into IP addresses, and ports point to the right service on that computer.
- Every time a page loads, my browser sends GET requests and the server replies with a status and a body.

## Key idea
Everything on the web is a conversation between a client and a server. Knowing how to read it in the Network tab is the base for web security.
