from pathlib import Path

# Define a custom, human-style GitHub README content
readme_content = """
# 👩‍💻 Yvonne Arteaga | Cybersecurity Enthusiast with an Engineer's Mind

![GitHub Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Yvonne%20Arteaga%20💻&fontSize=30&fontAlignY=40&desc=Cybersecurity%20%7C%20Networking%20%7C%20Engineer-Minded%20Creative&descAlignY=60)

## 🌟 About Me

Hi, I’m Yvonne — a recent Cybersecurity graduate with a passion for protecting people, playing phone games, and solving real-world problems. I enjoy building things, both virtually and technically. My interests include digital forensics, networking, and creative engineering projects.

## 🚀 What I Love
- 🧩 Phone games that challenge my brain (building block type!)
- 💡 Thinking like an engineer — problem-solving is my jam
- 🌐 Networking and securing digital systems
- 🐷 Collecting pig-themed stuff (yes, really!)
- 🎀 Mixing girl power with technical skills

## 🔧 Projects
- [Fuel Efficiency Calculator](https://github.com/Yvonne-Arteaga-Cyber/Fuel-Efficiency-Calculator): Simple Python script for MPG tracking
- [Network Traffic Analyzer](https://github.com/Yvonne-Arteaga-Cyber/Network-Traffic-Analyzer): A Wireshark + Python combo to examine packet data
- More projects coming soon! I’m organizing and adding previous coursework too.

## 🧠 Skills
`Python` | `SQL` | `Linux` | `Wireshark` | `FTK Imager` | `VMware` | `Networking Fundamentals` | `Microsoft Office Suite`

## 💖 Fun Extras
![PIGGY Badge](https://img.shields.io/badge/I%20Love-PIGS-pink)
![Cyber Nerd](https://img.shields.io/badge/Cyber-Nerd-blueviolet)
![Engineer Mind](https://img.shields.io/badge/Mindset-Engineer-orange)
![Networking](https://img.shields.io/badge/Networking-Enthusiast-informational)
![Gamer](https://img.shields.io/badge/Phone-Gamer-lightgrey)

---

📫 Let’s connect: [My LinkedIn](https://www.linkedin.com/in/yvonnearteaga/)  
🎮 Fun fact: I’m still undecided on ethical hacking… but curious!

"""

# Save to a README.md file
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content)

readme_path.name
