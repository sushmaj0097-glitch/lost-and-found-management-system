# 🎓 AI Lost & Found Management System - Campus Guardian

> **Only Arduino UNO Q + Gemma 4 (100% Offline)**
> Lost item ni AI tho match chesi, Arduino LED tho alert iche Smart Campus System.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Arduino](https://img.shields.io/badge/Arduino-UNO%20Q-teal)
![AI](https://img.shields.io/badge/AI-Gemma%204%20(gemma3%3A4b)-orange)
![Offline](https://img.shields.io/badge/Offline-Ollama-green)

## 🚀 Problem
College lo prathi roju ID cards, wallets, books pothuntayi. 
- Lost complaint register lo rastaru, evaru chudru
- Found item evaro thecharu - match ayyinda leda theliyadu
- ImageHash lanti old method only same photo ni match chestundi, meaning ardham chesukodu

## 💡 Solution
**Gemma 4 (gemma3:4b) + Arduino UNO Q**

Student "Blue ID card library lo poyindi" ani type chesthe:
- Gemma 4 meaning ardham chesukoni, Found items tho compare chestundi
- MATCH aithe Arduino UNO Q meeda LED blink / Matrix lo MATCH FOUND
- Admin ki mobile push notification (ntfy.sh)

Lost: `Blue ID card library` 
Found: `Library lo blue color ID dorikindi` 
-> **ImageHash: FAIL ❌ | Gemma 4: MATCH ✅**

## 🏛️ System Architecture
