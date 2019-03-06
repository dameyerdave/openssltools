# Openssl Tools
## Getting started
1. Create a root ca
```bash
otca create root
```
1. Create intermediate ca
```bash
otca create int
```
1. Create a server certificate
```bash
otca create server <servername>
```
1. Pack the certificates
```bash
otca pack <servername>
```
1. Use the certificate for your application
