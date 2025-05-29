
![Screen Shot 2025-05-29 at 10 53 29 PM](https://github.com/user-attachments/assets/9934daf8-1900-4fd8-917a-f3caa10c2acc)

```markdown
# 📬 ConsoleSoft Mailer CLI

A simple and powerful CLI tool for bulk email delivery—built by **Tim Adurah** under the **ConsoleSoft** brand.

## 🚀 Features

- CLI-based email shipping
- Easy email and write-up management via local files
- Per-project results tracking
- Quota display on launch
- Lightweight and efficient

---

## 🛠️ Setup & File Preparation

Before starting the tool, prepare the following two files **in the same directory**:

### 1. `emails` (no extension)
List of recipient email addresses. Example:

```

[example1@gmail.com](mailto:example1@gmail.com)
[user2@yahoo.com](mailto:user2@yahoo.com)
[test@example.org](mailto:test@example.org)

```

### 2. `writeup` (no extension)
Contains the subject, reply-to email, and HTML content.

**Format**:
```

subject: ConsoleSoft
replyto: [tim.adurah@gmail.com](mailto:tim.adurah@gmail.com)
writeup:<p style="font-family: Arial, sans-serif; font-size: 16px; color: #333333; line-height: 1.6;">
Greetings from the team!<br>
You received a message from <strong>Mr. Tope</strong>.<br> <a href="https://noderium.com" style="color: #1a73e8; text-decoration: none;">Visit us on Facebook</a>.

</p>
```

---

## 🧑‍💻 How to Use

### 1. Open Terminal in the Software Directory

### 2. Run the Software

You'll see your available quota.

### 3. Type `start` to begin

* You'll be prompted to enter a **project name** for this mailing batch.
* The app will then ask:
  `>>> Do you want to continue? (yes/no)`

### 4. If you say `yes`, the shipping process will begin.

* All emails from the `emails` file will be sent using the `writeup` content.
* Results will be saved in:
  `results/your-project-name/`

---

## 📊 Commands

| Command              | Description                           |
| -------------------- | ------------------------------------- |
| `start`              | Start a new mailing session           |
| `stop`               | Quit the application                  |
| `results`            | Show summary of all delivery attempts |
| `result get`         | List all delivery results             |
| `result get [email]` | Check result for a specific email     |
| `help`               | Display available commands            |
| `version`            | Show current version                  |

---

## 📂 Output

Each email's status (sent, failed, etc.) will be saved in:

```
results/your-project-name/
```

---

## 🧾 License

MIT License
© 2025 Tim Adurah — [ConsoleSoft](https://t.me/consolesoft)
