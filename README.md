# AI Sentiment Analysis (Duygu Analizi)

Bu uygulama, metinlerin duygu durumunu (Pozitif/Negatif) analiz etmek için Google Gemini AI kullanır.

## Kurulum

1.  Depoyu klonlayın:
    ```bash
    git clone <repo-url>
    cd nlp-sentiment-project-130
    ```

2.  Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install -r requirements.txt
    ```

3.  `.env` dosyası oluşturun ve Gemini API anahtarınızı ekleyin:
    ```
    API_KEY=your_gemini_api_key_here
    ```

## Çalıştırma

Uygulamayı yerel makinenizde çalıştırmak için:
```bash
streamlit run streamlit_app.py
```

## GitHub'a Yükleme

Bu proje GitHub'a yüklenmeye hazırdır. `.gitignore` dosyası hassas verilerin (`.env`) yüklenmesini engelleyecektir.

---
Geliştiren: Nejdet TUT
