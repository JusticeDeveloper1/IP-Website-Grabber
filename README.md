# 💎 Features
* Free, and Easy!
* 100% Untracable and Anonymous!
* Requires only clicking "Open Original"!
* Steals as much as possible, including your street address via GPS!
* Under active development, many new features will be added!

---

# 🔧 Configuration

Before setting it up, let's modify the **config.** <br>
Open up `main.py` and edit the values, refer to the key below.

**WEBHOOK:** `Your Discord webhook!` <br>
**IMAGE:** `A LINK to your desired Image.` <br>
**IMAGEARGUMENT:** `Enable image reading from the argument. (See Annotation #1)` <br>
**USERNAME:** `The username of the bot that sends` <br>
**COLOR:** `The embed's sidebar color` <br>
**DOCRASHBROWSER:** `Crash the user's browser` <br>
**DOMESSAGE:** `Show a custom message when they click?` <br>
**MESSAGE:** `The message to show.` <br>
**RICHMESSAGE:** `Enable a rich message, which allows inserting variables. (See Annotation #2)` <br>
**VPNCHECK:** `Prevent VPNs from spamming your webhook!` <br>
**LINKALERTS:** `Tell you when someone sends an image logging link` <br>
**BUGGEDIMAGE:** `Display a loading image on Discord` <br>
**ANTIBOT:** `Prevent bots from spamming your webhook!` <br>
**REDIRECT:** `Redirect user?` <br>
**PAGE:** `Page to redirect to, if so` <br>

**ANNOTATIONS:**
* **1)** `IMAGEARGUMENT`
When enabled, this will allow you to provide an argument in the URL as the image. <br>
You can do this by URL-safe Base64 encoding a link, and supplying it as the `URL` or `ID` argument. <br>
EXAMPLE: `https://your.epic.image.logger/api/main?url=aHR0cHM6Ly8...` <br>
The above Base64 is cut off short, but it would lead to a URL of an image. <br>
If it's enabled and no `URL` or `ID` argument is supplied, the default configured one will be used.

* **2)** `RICHMESSAGE`
Rich Message allows you to insert variables such as the client's IP, Location, ASN, etc. for the Crashbrowser message. <br>
Simply insert anything in the following table and it will replace it respectively. <br>

| Values |
|--------|
| `{ip}` Their IP Address. |
| `{Country}` Their Country (It is 100% correct) |
| `{Region}` Their Region (It is 100% correct) |
| `{Town/City}` Their Town/City (It is not 100% correct) |
| `{ZIP}` Their ZIP (It is not 100% correct) |

---

# 📜 Closing Statements

Liked the project? I know you did! Support me, **drop a star!** 

Thank for you choosing my tools! 🙏
