# Ad-hoc OpenVPN Server/Client configurator

This script allows to run a simple command on a server to provide simple
zero-config creation of a OpenVPN network. It provides an interface for clients
using the same script to retrieve one-time keys and certificates for connection,
using a simple plain text password protection.

This is **not** meant to provide a **secure** and reliable way to connect to a
VPN, but rather a fast and easy way to connect devices behind NATs or similar
systems that otherwise could not directly communicate.

Requires OpenVPN installed.
