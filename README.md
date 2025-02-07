# 🚀 GitHub Contribution Faker 🎭  

**📌 Disclaimer:** _This project is for educational purposes only. It demonstrates how automated scripts interact with GitHub repositories and should not be used for unethical purposes._  

<p align="center">
  <img src="https://camo.githubusercontent.com/1f5e411cd845b8f52dfbc40d206cbac23c8b9b8919c08a110390afc003aa8f9b/68747470733a2f2f6a656e6b696e732e6465762f67726170682e737667" width="600"/>
</p>  

## 📌 About  

This script **automates GitHub contributions** by making **false commits** at specific timestamps, effectively **peaking the GitHub contribution graph**. It utilizes **Node.js** and the following `npm` packages:  

✅ `jsonfile` → Manages JSON-based configurations.  
✅ `moment` → Generates timestamps for commit manipulation.  
✅ `random` → Randomizes commit timings.  
✅ `simple-git` → Interacts with Git repositories via Node.js.  

---

## 📂 Project Structure  

📦 github-bot
┣ 📜 index.js      # Main script for automating commits
┣ 📜 config.json   # Configuration for frequency, repo details
┣ 📜 package.json  # Node.js dependencies
┗ 📜 README.md     # This file!

---

## ⚡ Installation & Setup  

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/github-bot.git
cd github-bot

npm install

3️⃣ Configure the Script

Edit config.json to define:
	•	Number of commits per day.
	•	Time range for commits.

node index.js

<p align="center">
  <img src="https://media.giphy.com/media/5VKbvrjxpVJCM/giphy.gif" width="600"/>
</p>  


⚠️ Important Notes

🔹 This project is purely for educational purposes.
🔹 Use it on private repositories or test accounts.
🔹 Abusing GitHub’s contribution system may violate its policies.
