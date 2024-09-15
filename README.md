# Datagram

datagram is a Rust library that provides standardized traits for sending, receiving, encoding, and decoding datagram-based messages, such as those used in UDP communication. By defining a set of traits, datagram allows developers to implement custom datagram handling logic tailored to their specific needs.

## Features

* Datagram Sending and Receiving: Define custom behaviors for sending and receiving datagrams through traits.
* Encoding and Decoding: Easily encode data before sending and decode received data.
* Protocol Agnostic: Designed to work with any transport protocol that supports datagram-based communication.

## Installation

Add datagram to your Cargo.toml:

```toml
[dependencies]
datagram = "0.0.1"
```
