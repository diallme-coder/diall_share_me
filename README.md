# diall_share_me

Type anything, choose a 2-digit code, press Submit, and share it only as a QR code.

- The text is encrypted in the browser (AES-GCM, key derived from the code) and put into the link inside the QR code, after the `#`, so it is never sent to a server.
- Scanning the QR code opens the page, which asks for the 2-digit code. The wrong code shows "Wrong code"; the right one shows the message.
- Live page: https://diallme-coder.github.io/diall_share_me/

Note: a 2-digit code has only 100 possibilities, so it keeps casual viewers out but is not strong protection against someone determined who has the QR code.
