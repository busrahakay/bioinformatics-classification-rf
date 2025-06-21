# 🧬 Bioinformatics Classification with Random Forest  
FASTA formatında genetik dizilimlerden k-mer tabanlı özellik çıkarımı yapılarak Random Forest algoritması ile biyolojik sınıflandırma gerçekleştirildi.  
📚 Proje, “Biyoinformatiğe Giriş” dersi final ödevi kapsamında hazırlanmıştır.

---

## 📂 Veri Setleri ve Kaynaklar

- **dataset-dog.fasta**  
  🔗 https://www.ncbi.nlm.nih.gov/nuccore/AF013216.1?report=fasta  
  🧾 *Myxococcus xanthus DK 1622* bakterisinin metabolizmasında rol oynayan gen dizilimlerinden oluşur.

- **dataset-mushroom.fasta**  
  🔗 https://www.ncbi.nlm.nih.gov/nuccore/NM_080495.6?report=fasta  
  🧾 *Drosophila melanogaster* türüne ait "mushroom body defect" genine aittir. Öğrenme ve hafıza süreçleriyle ilgilidir.

---

## ✨ Proje Özellikleri

🔬 FASTA formatlı biyolojik dizilerden k-mer (alt dizi) çıkarımı  
📊 Sayısal özellik vektörlerinin oluşturulması  
⚙️ Random Forest ile sınıflandırma  
🔁 GridSearchCV ile hiperparametre optimizasyonu  
⚖️ SMOTE ile veri dengesizliği giderme  
📈 F1-score ve detaylı sınıflandırma raporu üretimi  
🧪 Pandas DataFrame ile analiz ve çıktı sunumu

---

## 📦 Kullanılan Kütüphaneler

- `pandas`, `numpy`, `collections.Counter`  
- `scikit-learn`: RandomForest, GridSearchCV, StandardScaler, train_test_split  
- `imblearn`: SMOTE  
- `matplotlib`, `seaborn` (görselleştirme için opsiyonel)

---

## 🚀 Projeyi Çalıştırmak İçin

```bash
git clone https://github.com/busrahakay/bioinformatics-classification-rf.git
cd bioinformatics-classification-rf
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
pip install -r requirements.txt
jupyter notebook Cennet_Büşra_Hakay_202113709007-RF.ipynb
