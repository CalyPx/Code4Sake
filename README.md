<!--
  You found the source. Respect.
  rohitpoudel020@gmail.com if you want to build something.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:064e3b,50:16a34a,100:4ade80&height=200&section=header&text=Rohit%20Poudel&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=55&desc=I%20build%20things%20Nepal%20actually%20needs&descAlignY=72&descSize=15&descColor=bbf7d0" width="100%"/>

</div>

<br>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=13&pause=800&color=4ADE80&center=true&vCenter=true&multiline=false&width=550&lines=%24+whoami+%23+CS+student+building+for+Nepal;%24+ls+wins%2F+%23+CivicCode+2026+Runner-up+%F0%9F%8F%86;%24+cat+sunuwa.txt+%23+When+Nepal+listens%2C+things+change;%24+git+push+origin+main+%23+always+shipping)](https://git.io/typing-svg)

</div>

---

```bash
┌──(rohit㉿nepal)-[~]
└─$ cat about.txt
```

```
Name     :  Rohit Poudel  (@CalyPx)
Status   :  CS Student + Builder
Location :  Nepal
Focus    :  Civic tech. Real datasets. Actual products.

I don't build portfolio projects.
I build things because the problem is real
and nobody else was going to do it.
```

---

```bash
┌──(rohit㉿nepal)-[~]
└─$ ls -la projects/
```

```
drwxr-xr-x  sunuwa/           🗣️  Civic voice platform         [🥈 CivicCode 2026]
drwxr-xr-x  harvo/            🌾  Farm-to-vendor marketplace    [🥉 PCPS Hackathon]
drwxr-xr-x  sajha-doctor/     🏥  Telehealth for rural Nepal
drwxr-xr-x  quakesafe-nepal/  🏚️  Earthquake damage prediction  [ML + FastAPI]
drwxr-xr-x  nepalprep/        📚  SEE exam prep platform
```

---

```bash
┌──(rohit㉿nepal)-[~/projects]
└─$ cat sunuwa/README.txt
```

> **"Sunuwa" (सुनुवाइ) means "a hearing" in Nepali.**
> **The name was not accidental.**

Nepal has a civic reporting problem. Citizens file complaints. Nothing happens. Not because the government doesn't care. Because there is no system that captures, routes, and tracks the issue to the right person.

**Sunuwa is that system.**

```
ARCHITECTURE
  Citizen   -->  Report (location + photo + category)
  System    -->  Routes to correct ward authority
  Authority -->  Receives structured, trackable complaint
  Public    -->  Watches issue status. Accountability is visible.

RESULT: The complaint doesn't disappear into a void anymore.
```

Built and shipped at **CivicCode Hackathon 2026** organized by Think Big.
Out of every team that showed up, Sunuwa walked away **Runner-up.**

`TypeScript` `Next.js` `Firebase`

---

```bash
┌──(rohit㉿nepal)-[~/projects]
└─$ cat harvo/README.txt
```

```
PROBLEM STATEMENT
  Farm gate price:   Rs. 20/kg
  Kathmandu price:   Rs. 80/kg
  Farmer receives:   25% of market value
  Who keeps the rest: middlemen
```

**Harvo cuts the middleman out entirely.**

Direct farm-to-vendor marketplace built for Nepal's agricultural reality:

- **Voice-guided Nepali interface** (Web Speech API) -- farmers shouldn't need to read to use a marketplace
- **Live Kalimati wholesale prices** scraped daily -- farmers know what their crop is actually worth
- **AI spoilage feasibility check** -- harvest date + road distance + shelf life = risk assessment before any order locks
- **eSewa escrow** -- vendor advance deposits build trust between strangers
- **Full EN / नेपाली toggle**

`React 18` `Node.js` `MongoDB` `Socket.io` `eSewa` `Web Speech API`

**Won Second Runner-up at PCPS College Hackathon.**

---

```bash
┌──(rohit㉿nepal)-[~/projects]
└─$ cat sajha-doctor/README.txt
```

NMC-verified doctors. Rural patients. No 6-hour bus ride to Kathmandu required.

Bilingual telehealth platform with digital prescriptions, medical record vault, and consultation analytics. Zero backend server. Fully Firebase-first.

`React 19` `Firebase` `Tailwind CSS` `Framer Motion`

---

```bash
┌──(rohit㉿nepal)-[~/projects]
└─$ python quakesafe/results.py
```

```python
dataset   = "2015 Gorkha Earthquake Survey (DrivenData)"
buildings = 260_601
features  = 38
target    = "damage_grade"  # Low / Medium / High

results = {
    "Decision Tree"    : {"accuracy": "65.25%", "f1": 0.60},
    "Random Forest"    : {"accuracy": "69.43%", "f1": 0.66},
    "XGBoost + SMOTE"  : {"accuracy": "74.45%", "f1": 0.70},  # <-- deployed
}

# 5 custom features engineered manually
# volume_proxy ranked 4th in overall feature importance
# deployed via FastAPI -> returns Preparedness Score /100
```

`Python` `XGBoost` `scikit-learn` `SMOTE` `FastAPI` `Pandas`

---

```bash
┌──(rohit㉿nepal)-[~]
└─$ cat skills.json
```

```json
{
  "frontend"  : ["React", "Next.js", "TypeScript", "Tailwind CSS", "Framer Motion"],
  "backend"   : ["Node.js", "Express", "FastAPI", "MongoDB", "Firebase", "Socket.io"],
  "ml_data"   : ["XGBoost", "scikit-learn", "SMOTE", "Pandas", "NumPy", "Jupyter"],
  "payments"  : ["eSewa"],
  "other"     : ["Web Speech API", "D3-geo", "JWT", "Multer", "joblib", "Vite"]
}
```

---

```bash
┌──(rohit㉿nepal)-[~]
└─$ git log --oneline --hackathons
```

```
a3f1c2d  (HEAD)  Runner-up       CivicCode Hackathon 2026 (Think Big)  -- Sunuwa
b8e4f1a           2nd Runner-up   PCPS College Hackathon                 -- Harvo
```

---

```bash
┌──(rohit㉿nepal)-[~]
└─$ neofetch
```

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=CalyPx&show_icons=true&theme=github_dark&hide_border=true&count_private=true&title_color=4ade80&icon_color=4ade80&bg_color=0d1117&ring_color=16a34a" height="150"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CalyPx&layout=compact&theme=github_dark&hide_border=true&title_color=4ade80&bg_color=0d1117" height="150"/>

</div>

<div align="center">

![Streak](https://streak-stats.demolab.com?user=CalyPx&theme=github-dark-blue&hide_border=true&ring=4ade80&fire=16a34a&currStreakLabel=4ade80&background=0d1117)

</div>

---

```bash
┌──(rohit㉿nepal)-[~]
└─$ ping rohit --contact
```

```
PING rohit (rohitpoudel020@gmail.com)
```

<div align="center">

[![Gmail](https://img.shields.io/badge/rohitpoudel020%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohitpoudel020@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Rohit%20Poudel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohit-poudel-633364310/)
[![GitHub](https://img.shields.io/badge/CalyPx-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CalyPx)

**Open to hackathons, collabs, and problems worth solving.**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:4ade80,50:16a34a,100:064e3b&height=120&section=footer&fontSize=18&fontColor=ffffff&text=Nepal%20has%20real%20problems.%20I%20show%20up%20and%20build.&fontAlignY=55" width="100%"/>

</div>
