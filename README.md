# 🎧 WhisPol – Transkrypcja i tłumaczenie głosu (AR → PL)

**WhisPol** to narzędzie oparte na modelach AI, które:
1. Transkrybuje mowę z pliku audio (np. po arabsku) przy użyciu modelu Whisper.
2. Tłumaczy uzyskany tekst na język polski przy użyciu modelu MarianMT.
3. Zapisuje wynik do pliku tekstowego.

---

## 🚀 Funkcje
- 🎤 Rozpoznawanie mowy z plików audio (`.mp3`, `.wav`)
- 🌍 Automatyczne tłumaczenie tekstu z arabskiego na polski
- 💾 Zapis tłumaczenia do pliku `.txt`
- 🔧 Prosta konfiguracja i możliwość rozbudowy (np. GUI, inne języki)

---

## 🧠 Technologie
- [OpenAI Whisper](https://github.com/openai/whisper) – transkrypcja mowy  
- [Hugging Face Transformers](https://huggingface.co/transformers/) – tłumaczenie  
- [Python 3.9+](https://www.python.org/)  
- (opcjonalnie) [Gradio](https://gradio.app/) – prosty interfejs webowy

---

## ⚙️ Instalacja

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/twoj-login/WhisPol.git
   cd WhisPol
