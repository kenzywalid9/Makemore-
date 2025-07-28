#  Makemore-Arabic: Arabic Name Generation using Autoencoder

This project aims to generate realistic **Arabic names** using a character-level **Autoencoder** model.

---

##  Project Overview

Name generation is a fun and practical application of generative models in natural language. While most name generators use RNNs or Transformers, this project explores a **character-level Autoencoder** to:

- Learn compact latent representations of Arabic names
- Reconstruct names from these representations
- Generate new names by sampling the latent space

---

##  Why Arabic Names?

Arabic names are rich in culture and morphology, making them interesting for generative modeling:

- Unique character set (non-Latin script)
- Rich combinations and stylistic patterns
- Useful for creative writing, naming bots, or cultural datasets

---

##  Dataset

We use a custom dataset of Arabic names (first names only), cleaned to contain:

- Arabic letters only (no numerals, diacritics, or Latin characters)
- One name per line
- Examples: `علي`, `فاطمة`, `ياسين`, `سارة`

 **Dataset Source**:  
[🔗 Arabic Names Dataset on Kaggle](https://www.kaggle.com/datasets/lailamohammed/arabic-names)

