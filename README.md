# Basic Web Input Fuzzer (Python)

## Overview
This project demonstrates a beginner-friendly fuzzing technique used in
ethical hacking to test how a web application handles unexpected or random input.

The project uses a locally hosted web application to ensure all testing is
ethical and safe.

---

## Project Components

### 1. Test Server
A simple Flask web application that simulates a login endpoint and responds
to user input.

### 2. Fuzzer
A Python script that sends random and malformed input to the server and
records the response behavior.

---

## Tools & Technologies
- Python 3
- Flask
- Requests library
- Command Prompt (Windows)

---

## How It Works
1. The Flask server runs locally on `127.0.0.1`
2. The fuzzer sends random payloads to `/login`
3. The server responds with a message
4. The fuzzer logs:
   - HTTP status code
   - Response length

---

## Sample Output
[0] Status: 200 | Response length: 22
[1] Status: 200 | Response length: 23

---

## Ethical Disclaimer
This project is for educational purposes only.
All testing was conducted on a locally hosted application owned by the author.
No real systems or external networks were tested.

---

## Author
Beginner Ethical Hacking Project
