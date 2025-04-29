📄 PDF Chatbot - Çoklu PDF ile Sohbet Asistanı
Bu uygulama, birden fazla PDF dosyasından bilgi çıkararak bu bilgilerle sohbet etmenizi sağlar. Kullanıcı tarafından yüklenen PDF dosyaları metne dönüştürülür, anlamlı parçalara bölünür, vektör veritabanına dönüştürülür ve LLaMA modeliyle entegre edilerek akıllı bir sohbet deneyimi sunar.

🚀 Özellikler
Birden fazla PDF dosyasını aynı anda işleyebilme

Gelişmiş metin bölme (chunking) algoritması

HuggingFace üzerinden MiniLM tabanlı embedding kullanımı

FAISS ile hızlı vektör arama

Meta-LLaMA modeli ile doğal dilde soru-cevap

Önceki sohbet geçmişini hatırlayan konuşma hafızası

🛠️ Gereksinimler
Python 3.9+

streamlit

langchain

PyPDF2

transformers

faiss-cpu

huggingface_hub

python-dotenv

pyngrok

📦 Kurulum
bash
Kopyala
Düzenle
git clone https://github.com/kullanici-adi/pdf-chatbot.git
cd pdf-chatbot
pip install -r requirements.txt
.env dosyası oluşturun ve Hugging Face token bilgilerinizi girin:

ini
Kopyala
Düzenle
HUGGINGFACE_TOKEN=your_token_here
▶️ Uygulamayı Başlatma
bash
Kopyala
Düzenle
python app.py
📁 Kullanım
Sol menüden bir veya daha fazla PDF dosyası yükleyin.

"İşle" butonuna tıklayın.

Sohbet kutusuna sorularınızı yazın ve PDF'lerinizle etkileşime geçin!

⚠️ Not
Kodun başında geçen ngrok.kill() ve ngrok bağlantısı, uygulamada eksik veya tanımsız olabilir. Ngrok entegrasyonu sağlanacaksa ayrıca yapılandırılması gerekir.
