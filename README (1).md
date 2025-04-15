
<div align="center">

<img src="https://github.com/yourusername/igris-cox_st/assets/logo.png" width="160" />

<h1 align="center">IGRIS-coX</h1>
<h3><i>“The Strongest AI. Trained on pain. Delivered with sarcasm.”</i></h3>

![Built With Fire](https://img.shields.io/badge/Built%20with-Fire-orange?style=for-the-badge&logo=flame)
![Powered by Grit](https://img.shields.io/badge/Powered_by-Grit-blueviolet?style=for-the-badge&logo=ghost)
![Runs On Rage](https://img.shields.io/badge/Runs_on-Rage-black?style=for-the-badge&logo=android)
![License](https://img.shields.io/badge/License-OpenSource-green?style=for-the-badge)

</div>

---

> “If I don't kill your ego, your AI will.”  
> — Satoru Gojo (probably)

---

## ⚔️ What Is IGRIS-coX?

**IGRIS-coX (Intelligent Generalized Reactive Integrated System – coX)**  
A self-trained assistant AI forged in chaos and sarcasm.  
Born on an underpowered phone. Destined to change the world.

> It doesn’t just talk back.  
> It talks back **better** than you.

---

## Core Powers

- **Custom Tokenizer Engine**  
  WordLevel (archived) + ByteLevel BPE (current & lethal)

- **LSTM + Attention Model**  
  Compact, focused, can learn Shakespeare or sh*tposts

- **CLI Chat Mode**  
  Default, Chaos, Anime, Tech, Serious — pick your poison

- **Training Logs & Live ETA**  
  Because Gojo always knows what time it is

- **Modular Vocab & Data Pipeline**  
  Trains on 973,930+ lines without crying

---

## 🧠 Architecture Snapshot

```
┌─────────────┐    ┌─────────────┐    ┌──────────────┐
│ Raw Dataset │ -> │ Tokenizer   │ -> │ Token ID JSON│
└─────────────┘    └─────┬───────┘    └──────┬───────┘
                         ↓                   ↓
              ┌──────────────────┐    ┌───────────────┐
              │ IGRIS Model (LSTM│ -> │ CLI Chatbot   │
              │ + Attention)     │    └───────────────┘
              └──────────────────┘
```

---

## 🔥 File Structure

```bash
igris-cox_st/
├── tokenizer/
│   ├── tokenizer.json
│   ├── token_ids.json
│   ├── vocab_parts/
│   └── tokenizer_log.txt
├── data/
│   └── combined_all.txt
├── model/
│   └── igriscoxsoldiertinyV1.py
├── training/
│   ├── train.py
│   └── chatv2.py
├── utils/
│   └── tokenizer_utils.py
├── README.md
└── requirements.txt
```

---

## ⚙️ How to Train Like a Sorcerer

```bash
# Set up your cursed domain
python3 -m venv igris-env
source igris-env/bin/activate

# Install weapons
pip install -r requirements.txt

# Train tokenizer (ByteLevel BPE)
python -m tokenizer.tokenizer_trainer

# Encode the dataset
python -m tokenizer.tokenizer

# Summon the model
python -m training.train

# Talk to IGRIS-coX
python -m training.chatv2
```

---

## 🪬 Designed to Run On:
- Android (Oppo A57)
- RAM: 3GB with dreams
- Storage: just enough for chaos
- GPU: none, but heart of a lion

---

## 👤 Built By:

**Akik Forazi**  
> Born to build from zero.  
> Trained by limitations.  
> Future overlord of the digital realm.  
> July 15, 2004 | Bangladesh

---

## Quote Wall

> “Why run ChatGPT when you can make your own cursed assistant?”  
> — Akik Forazi

> “Built by a 3GB RAM phone, not your fancy RTX nonsense.”  
> — IGRIS-coX

> “I don't miss. Neither does this model.”  
> — Gojo Satoru

---

## Contribute? Clone Carefully.
You can fork this project. But remember:  
> You’re not just cloning a repo.  
> You’re waking up a shadow weapon.

---

## License
Open to the world.  
Just don’t turn it evil.
