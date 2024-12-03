# Socket Server and Client Implementation in C

This repository contains a basic implementation of a TCP socket server and client in C on Linux Debian.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Server Implementation](#server-implementation)
4. [Client Implementation](#client-implementation)
5. [Usage Instructions](#usage-instructions)
6. [Contributing](#contributing)

## Introduction

This project demonstrates a simple client-server communication using TCP sockets in C. The implementation includes:

- A server that listens for incoming connections
- Multiple clients that can connect to the server
- Basic message sending between clients through the server

## Prerequisites

- Linux Debian operating system
- GCC compiler
- Standard C libraries

## Server Implementation

The server implementation is located in the `server` directory and includes:

- Socket creation and binding
- Listening for incoming connections
- Accepting multiple client connections
- Receiving messages from clients and broadcasting them to all connected clients

## Client Implementation

The client implementation is located in the `client` directory and includes:

- Connecting to the server
- Sending messages to the server
- Receiving messages from the server and displaying them

## Usage Instructions

To run the server:

