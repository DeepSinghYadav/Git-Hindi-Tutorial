# कोड के उदाहरण (Code Snippets)

यहाँ Git के इस्तेमाल के असली उदाहरण दिए गए हैं। इन्हें आप सीधे अपने टर्मिनल (Terminal) पर इस्तेमाल कर सकते हैं।

---

## 📍 Checkpoint-1: नए प्रोजेक्ट की शुरुआत (Setup)

**उद्देश्य:** एक नया फोल्डर बनाना और उसे Git से जोड़ना।

### 1. फोल्डर बनाना और उसके अंदर जाना
mkdir my-new-project
cd my-new-project

### 2. Git को भविष्य के लिए सेट करना (Global Settings)
*यह कदम पूरे कंप्यूटर में सिर्फ एक बार करना होता है।*
git config --global init.defaultBranch main
git config --global user.name "Deep Singh Yadav"
git config --global user.email "your-email@example.com"

### 3. Git चालू करना और चेक करना
git init
git status

### 4. अगर अभी भी 'master' दिख रहा हो, तो उसे 'main' करें
git branch -M main

---
*नोट: ये कमांड्स आपके प्रोजेक्ट की नींव (Foundation) रखती हैं।*