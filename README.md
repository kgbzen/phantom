<div align="center">
  <p align="center">
    <img alt="ss1" src="https://raw.githubusercontent.com/f34rl00/phantom/main/images/logo_6_scaled_white.png">
  </p>
  <h1>
    phantom
  <h1>
  <h2>
    Secure instant messaging app using sockets, written in python
  </h2>
  <b>
    Currently under development in a private repository.
  </b>
</div>

## Installation of the demo app with the Debian Release
```
## Clone the repo
git clone https://github.com/f34rl00/phantom

## Change your directory
cd phantom/demo/phantom

## To install and run the server application:
./SERVER_INSTALLER.sh
cd server
python server.py

## To install and run the client application:
./CLIENT_INSTALLER.sh
cd client
python client.py
```

### Problems and TODO List:
- [ ] Graphical User Interface with PyQT https://wiki.python.org/moin/PyQt
- [ ] Create Documentation with https://readthedocs.org/
- [ ] Compare protocol with Signal's protocol and Session's protocol
- [ ] MITM Attack Mitigation ?
- [ ] Video Call
- [ ] Encrypted voice call
- [ ] Digital Signatures and certification
- [ ] Faster file transfer
- [ ] Chat rooms
- [ ] Onion routing + noise for messages ?
- [ ] Tor Routing with Orbot ?
- [ ] Check Curve25519 / AES-256 / HMAC-SHA256
- [ ] Transparency Report
- [ ] Limit login attemps and ip banning
- [ ] During chat system commands
- [ ] Realpath error in file location
- [ ] Mailbox feature
- [ ] Sending files while the receiver is offline
- [ ] Sending messages while the receiver is offline
- [ ] Saving login credentials in a config file #optional
- [ ] Disable visible password during registration
- [ ] Broken pipe error on server
- [ ] Increase chunck size to lower latency in voice calls
- [ ] Message, voice call and video call without registration using a shared-OTP (one time password)
- [ ] Am I really using E2EE ?
- [ ] Contact verification ?
- [ ] Perfect Forward Secrecy ?
- [ ] Encrypting metadata ?
- [ ] TLS/Noise to encrypt network traffic ?
- [ ] Certificate pinning ?
- [ ] 2FA or MFA ?
- [ ] Option to disable timestamp logging
- [ ] Self destructing messages ?
- [ ] Strip Meta-Data from Media
- [ ] Decentralized Platforms
- ~~[ ] switching from mariadb to sqllite~~
- [x] Automatic Installation (for both client and server)
- [x] Test Automatic Installer with virtual machine
- [x] A better logo :\
- [x] Python 3 port
- [x] Voice call
- [x] Encoding error between operating systems
- [x] Disable Visible password during login
- [x] Interference of ongoing and coming messages during chat
- [x] Colored messages!
- [x] Change file location prompt for file transfer
- [x] Guest commands
- [x] Press ESC to exit
- [x] Single line login for connecting to server
- [x] Design a bad logo for the app
- [x] Autologin with the "-i" parameter
- [x] Simultaneously message and voice call with seperated sockets

## Help to keep this project alive
- Bitcoin: 34J7KM8pq8rhzVgdhCuTT6tcSQheSAPRDN
