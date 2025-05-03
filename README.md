  Silent-Logger-Keylogger
  🔍 Silent Logger – Python Keylogger

**Silent Logger** is a lightweight Python-based keylogger designed for ethical hacking demonstrations and cybersecurity education. It records every keystroke made by the user and stores it in a local log file. The keylogger runs silently in the background and gracefully exits when the `Esc` key is pressed.

---

   ⚠️ Disclaimer

This tool is intended **only for ethical and educational use**. Unauthorized use of keyloggers on systems or individuals without consent is illegal and unethical.

---

   📌 Features

- ✅ Real-time key capture
- ✅ Stores logs in `key_log.txt` with timestamps
- ✅ Graceful shutdown using `Esc` key
- ✅ Session header marking new logging sessions
- ✅ Minimal dependencies and clean code

---

   🛠️ Tech Stack & Tools

| Technology | Purpose                        |
|------------|--------------------------------|
| Python 3   | Core programming language      |
| `pynput`   | Capturing keyboard inputs      |
| `os`       | Session marker/file handling   |
| .txt file  | To store logs                  |
| CMD/VS/etc | Execution environment          |

---

   📂 File Structure

Silent-Logger-Keylogger/
├── main.py # Keylogger script
├── key_log.txt # (Generated) keystroke logs
├── README.md # Project documentation

---

   ▶️ How to Run

1. **Install dependencies**:
--> pip install pynput

3. **Run the script**:

5. **Press `Esc`** to stop the keylogger and close the session.

6. **View logs** in the `key_log.txt` file.

---

💡 Example Output (key_log.txt)

 New Session Starts
h
e
l
l
o
Key.space
w
o
r
l
d

---

  🧠 Use Case

This project helps learners understand:

- How keyloggers work under the hood
- The basics of system input capture
- The importance of ethical hacking in identifying threats
- Why endpoint protection is crucial in cybersecurity

---





