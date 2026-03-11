# 🌸 Idol Factory: Love Edition

> A fandom-based AI relationship service where you become a fan of an AI idol — and through fan activity and competition, evolve into their **one and only special person.**

---

# ✦ Overview

**Idol Factory: Love Edition** is a mobile web experience built around **K-pop fandom culture**.

Users can fan an official AI idol, earn **fan points** through chat, gifts, and cheers, and climb the **fan ranking** to unlock exclusive late-night events and video calls.

Beyond just being a fan — users can also create their **own AI idol through the Factory**, building a character from a prompt and watching them come to life as a card on the home feed.

---

# ✦ Features

## 🏠 Home Feed

- Trending idol cards with **fan counts, hashtags, and relationship badges**
- Onboarding flow  
  `Nickname → Preference Tags → Character Recommendation`
- Returning users go directly to **Home Feed**

---

## 👤 Character Page

- Character profile with **concept, hashtags, and fan stats**
- Relationship stage tracker  


Fan → Devoted → Top Fan → Secret Crush → My Person ♥


Fan activity grid:


Chat / Gift / Cheer / Video Call


Additional features:

- Gift bottom sheet with **fly animation**
- Character reaction after gift
- **Fan ranking TOP 3** per character

---

## 💬 Chat

- Preset dialogue with **Jinwoo** (8 rotating responses)
- Relationship-stage-based background themes  

| Stage | Theme |
|------|------|
| Fan | Mint |
| Devoted | Pink |
| Top Fan | Purple |
| Secret Crush | Dark |
| My Person | Black / Gold |

Features:

- Fan point accumulation
- Level-up popup
- Quick reply buttons
- Typing indicator

---

## 🎉 Event

Unlocked at **Top Fan (500p)**

**Late Night Message Scenario**

- Novel game style dialogue
- Rooftop night background
- **3-choice branching system**

Each choice:

- triggers different dialogue
- gives different fan points

Completing the event unlocks **Secret Crush stage**

---

# ✦ Factory

Create your **own AI Idol**

Input fields:

- Name
- Prompt
- Personality tags
- Style

Features:

- Tag-based preset image matching  
  `(bright / dark)`
- Loading animation with generation messages
- Generated idol card automatically registered on **Home Feed**

---

# 📹 Video Call (팬영통)

Features:

- Connecting screen with **pulse animation**
- Looping idol video with **real-time chat overlay**
- Call timer
- Auto idol message every **7 seconds**

End screen:

- Call summary
- Fan points gained

---

# 🏆 Ranking

Two ranking systems:

### Weekly Idol Ranking

- Based on **total fan count**
- Top idol featured with **crown animation**

### Fan Ranking (Per Idol)

- **TOP 10 leaderboard**
- Only **#1 fan earns the Top Fan badge**

---

# ✦ Dual Ranking System

Idol Factory introduces **two layers of competition**.

| System | Description |
|------|------|
| Fan Ranking | Compete with other fans of the same idol |
| Idol Ranking | Support your idol to raise their platform-wide ranking |

The more fans support an idol, the higher the idol climbs — tapping into the **collective fandom drive** of:

> *"I want my idol to be #1."*

---

# ✦ Relationship Stages

| Stage | Condition | Vibe |
|------|------|------|
| Fan 🌱 | First registration | Bright, polite |
| Devoted 💗 | 100 points accumulated | Familiar, calls your name |
| Top Fan 👑 | 500p + Ranking #1 | Hints at something special |
| Secret Crush 💜 | 1 event cleared | Just the two of you |
| My Person ♥ | 3 events cleared | Fully intimate |

---

# ✦ Official Characters

| Name | Concept | Tags |
|----|----|----|
| 진우 (Jinwoo) | Charismatic Band Vocal | #강렬한눈빛 #나만바라봐 #무대위와사생활다름 |
| 카이 (Kai) | Cold Genius Idol | #츤데레끝판왕 #차갑지만챙겨줌 #알고보면순함 |
| 렌 (Ren) | Dreamy Pop Idol | #따뜻한오빠 #은근집착 #눈웃음치명적 |

---

# ✦ Design System

**UI Style**

Y2K Retro Windows UI  
Checkered backgrounds, pixel windows, retro YES/NO buttons

**Color Palette**

| Color | Hex |
|------|------|
| Pastel Pink | `#FFB7C5` |
| Lavender | `#D4B8E0` |
| Mint | `#B8E8D0` |
| Yellow | `#FFF3B0` |

**Fonts**

- Press Start 2P (titles / logo)
- Noto Sans KR (body)

**Screen Size**


390 × 844px
(iPhone portrait)


Desktop view shows a **centered phone frame UI**

---

# ✦ File Structure


idol-factory/
├── index.html # Onboarding + Home feed
├── character.html # Character detail + Fan activity
├── chat.html # 1:1 preset chat
├── event.html # Top Fan event scenario
├── factory.html # Idol creation
├── videocall.html # Fan video call
├── ranking.html # Weekly idol & fan ranking
└── assets/
├── logo.png
├── jinwoo.png
├── jinwoo_header.png
├── jinwoo_full.png
├── kai.png
├── ren.png
├── preset_bright.png
├── preset_dark.png
├── bg_rooftop.png
└── jinwoo_call.mp4


---

# ✦ Tech Stack

- Vanilla **HTML / CSS / JavaScript**
- **Single-file per page**
- All scripts inline

State management:


localStorage


Stores:

- nickname
- fan points
- relationship stage

Deployment:


GitHub Pages


No external API calls — **fully preset-based PoC**

---

# ✦ PoC vs Vision

| Feature | PoC | Future Vision |
|------|------|------|
| Character Dialogue | Preset responses | LLM persona-based generation |
| Character Visuals | Preset images | AI image generation |
| Idol Creation | Tag → preset matching | LLM auto persona creation |
| Event Scenarios | Fixed branching | Dynamic AI narrative |
| Video Call | Looping video | AI real-time video + lipsync |

---

---

> **"나만 보면 돼." — Jinwoo 💗**
