<h1 align="center">🧠 CyberDex — The Cybersecurity Pokédex</h1>
<p align="center">
  A hacker’s encyclopedia of cybersecurity tools, explained in plain English with flags, usage examples, and cool ASCII banners.  
</p>

---

## ⚡ What is CyberDex?

CyberDex is a collection of cybersecurity tools explained like a Pokédex — one markdown file at a time.  
Each page includes:

- 🛠️ **Tool Purpose**
- 🧪 **Common Flags**
- 🧠 **Usage Examples**
- 💡 **Tips & Tricks**
- 🎨 **ASCII Banner**
- 📦 **Official Links**

---

## 🗂️ Tools Covered

| Tool         | Description                      |
|--------------|----------------------------------|
| `nmap`       | Network scanner & port mapper    |
| `nikto`      | Web vulnerability scanner        |
| `burpsuite`  | Intercept web requests/responses |
| `metasploit` | Exploit framework for pentesting |
| ...more soon | You can contribute too! 👇       |

---

## 🤝 Contribute

Want to add a tool?

1. Fork this repo
2. Copy the tool template below
3. Add your tool in `tools/toolname.md`
4. Make a pull request!

---

## 📄 Tool Template

```md
# Tool Name: [e.g., Nmap]

## 🔍 Description:
A short one-liner about what the tool does.

## ⚙️ Common Flags:
- `-sV`: Detect service/version info
- `-O`: OS detection
- `-A`: Aggressive scan mode

## 🚀 Example Usage:
```bash
nmap -A 192.168.1.1
