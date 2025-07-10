# Alfido Tech Internship - Task 3: Password Cracking 🔐

## 🔧 Tools Used:
- **John the Ripper**: A powerful password cracking tool used in cybersecurity.
- **Kali Linux**: Operating system used to run John the Ripper.
- **Wordlist**: `rockyou.txt`, a popular password dictionary.

## 📝 Task Objective:
To perform a brute-force password cracking attack on a given password hash using John the Ripper and identify the plaintext password.

## 🧪 Steps Performed:
1. Created a file `hash.txt` and added the MD5 hash.
2. Used `john` with the rockyou wordlist:
   ```bash
   john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt
After cracking, displayed result using:
john --show hash.txt
✅ Result:
The password 12345 was successfully cracked from the given hash.
