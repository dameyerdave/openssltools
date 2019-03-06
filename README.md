# Openssl Tools
## Getting started
1. Create a root ca
```bash
otca create root
```
2. Create intermediate ca
```bash
otca create int
```
3. Create a server certificate
```bash
otca create server <servername>
```
4. Pack the certificates
```bash
otca pack <servername>
```
5. Use the certificates in your application
