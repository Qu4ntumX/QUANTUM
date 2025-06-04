# 🤖 QUANTUM - Assistant IA personnel

QUANTUM est un assistant IA personnel **auto-hébergé**, conçu pour générer du texte, de l’audio, des images, et interagir vocalement.  
Accessible depuis n’importe quel terminal ou interface web, il est pensé comme un **JARVIS minimaliste** 100% personnalisé.

---

## 🧠 Fonctionnalités prévues
- 🔊 Synthèse et reconnaissance vocale (offline/online)
- 💬 Génération de texte (LLM local ou API)
- 🎨 Génération d'images (via Stable Diffusion / DALL·E)
- 📖 Apprentissage autonome (mémoire contextuelle)
- 💻 Commandes système (scripts vocaux personnalisés)
- 🌐 Accessible depuis n'importe où (web, LAN, SSH)

---

## 🏗️ Architecture (VM)
- OS : Linux Debian / Ubuntu
- Hyperviseur : VMware
- Services :
  - Interface vocale (VOSK / Whisper)
  - Traitement texte (GPT / Ollama)
  - Stockage local / chiffré
  - API REST / Interface Web minimaliste

---

## 🚧 En cours de développement
- [x] VM de base fonctionnelle
- [ ] Implémentation des modules vocaux
- [ ] Intégration LLM local (Ollama / LM Studio)
- [ ] Connexion à des APIs d'image
- [ ] Interface utilisateur CLI + Web

---

## 🛠️ Stack envisagé
Python · Bash · VOSK · Whisper · Ollama · Streamlit · SQLite · Git

---

## 📄 Docs associées
- `/docs/roadmap.md` → Feuille de route détaillée
- `/prompts/` → Prompts utiles pour guider QUANTUM
- `/scripts/` → Automatisations locales
