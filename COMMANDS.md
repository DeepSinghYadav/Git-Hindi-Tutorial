# Git कमांड्स (Cheat Sheet)

## Checkpoint-1 मे इस्तेमाल की गई नई commands
| कमांड | क्या काम करती है? |
| :--- | :--- |
| `git config --global init.defaultBranch main` | यह सुनिश्चित करता है कि भविष्य में हर बार नई ब्रांच का नाम 'main' ही रहे। |
| `git init` | खाली Git रिपॉजिटरी की शुरुआत करना। |
| `git status` | वर्तमान स्थिति की जाँच करना। |
| `git branch -M main` | अगर ब्रांच का नाम 'master' दिख रहा है, तो उसे बदलकर 'main' करना। |
| `git remote add origin <URL>` | लोकल फोल्डर को ऑनलाइन GitHub से जोड़ना। |
| `git push -u origin main` | पहली बार कोड को GitHub पर भेजना और लिंक सेट करना। |
| `git push` | अगली बार से सिर्फ एक शब्द लिखकर कोड भेजना। |

## Checkpoint-2 मे इस्तेमाल की गई नई commands

कमांड,क्या काम करती है?
git diff,पिछले Commit और वर्तमान काम के बीच का अंतर (Changes) देखना।
सुझाव: अगर git diff या git log देखते समय आप टर्मिनल में 'अटक' जाएं, तो हमेशा q दबाकर बाहर निकलें।
git checkout -- <file>,किए गए बदलावों को मिटाकर फाइल को वापस पुराने जैसा करना।