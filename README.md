# 📚 PDF Chatbot – Retrieval-Augmented Information System

Bu proje, kullanıcıların PDF dosyalarından doğal dilde soru sorarak bilgi almasını sağlayan bir **bilgi alma sistemi (Information Retrieval System)** sunar. Google Gemini LLM ve HuggingFace embedding’leri ile desteklenen bu sistem, vektör veritabanı kurarak PDF içeriğine dayalı sohbet deneyimi sağlar.

![Demo](assets/demo.gif) <!-- Eğer demo GIF’in varsa buraya ekle -->

---

## 🚀 Özellikler

- 📄 PDF dosyalarından metin çıkarma
- 🔍 Metni parçalara ayırma (chunking)
- 📦 FAISS ile vektör veritabanı oluşturma
- 🧠 Google Gemini (LLM) ile anlamlı cevap üretme
- 💬 Chat arayüzü ile etkileşimli sohbet
- ⚡️ Streamlit tabanlı kolay kullanım arayüzü

---

## 📦 Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|----------|----------|
| [Streamlit](https://streamlit.io/) | Web tabanlı uygulama arayüzü |
| [LangChain](https://www.langchain.com/) | LLM zincirleme ve retrieval altyapısı |
| [Google Gemini](https://deepmind.google/technologies/gemini/) | LLM (via `langchain_google_genai`) |
| [FAISS](https://github.com/facebookresearch/faiss) | Vektör veritabanı |
| [HuggingFace Sentence Transformers](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) | Embed modeli |
| [PyPDF2](https://pypi.org/project/PyPDF2/) | PDF sayfalarından metin çıkarma |
| [dotenv](https://pypi.org/project/python-dotenv/) | Ortam değişkeni yönetimi |

---

## 🛠️ Kurulum

1. Bu repoyu klonlayın:
```bash
git clone https://github.com/kullanici-adiniz/pdf-chatbot.git
cd pdf-chatbot
```

2.Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```

3. Ortam değişkenlerinizi ayarlayın:
```bash
GEMINI_API_KEY=your_google_gemini_api_key
```

4. Uygulamayı başlatın:
```bash
streamlit run app.py
```


