# Git और GitHub: शून्य से शिखर तक 🚀

यह प्रोजेक्ट Git और GitHub सीखने की मेरी यात्रा का एक दस्तावेज़ है। यहाँ सभी कमांड्स और स्टेप्स को सरल भाषा में समझाया गया है।

## 🛠 अभी तक का सफर (Quick Notes)

### 1. Setup (एक बार के लिए)
- **पहचान सेट करना:**
  - `git config --global user.name "आपका नाम"`
  - `git config --global user.email "आपका ईमेल"`
- **डिफ़ॉल्ट ब्रांच हमेशा `main` रखना:**
  - `git config --global init.defaultBranch main`

### 2. Daily Workflow (रोजाना का काम)
| कमांड | विवरण |
| :--- | :--- |
| `git init` | नए प्रोजेक्ट में Git शुरू करना |
| `git status` | फाइलों की वर्तमान स्थिति (State) चेक करना |
| `git add .` | सभी बदलावों को **Staging Area** में डालना |
| `git commit -m "संदेश"` | बदलावों को **Local Repository** में स्थायी रूप से सेव करना |
| `git branch -M main` | वर्तमान ब्रांच का नाम बदलकर **main** करना |

### 3. GitHub (Remote) से जोड़ना
- **Remote जोड़ना:** `git remote add origin <URL>`
- **कोड भेजना:** `git push -u origin main`

---
*नोट्स बनाने वाला: दीप सिंह यादव*