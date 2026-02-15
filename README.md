# 🤖 AI Keyword Clustering Tool

An AI-powered keyword clustering tool that automatically groups similar keywords using machine learning (K-Means clustering).

## 📋 Project Overview

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to cluster SEO keywords into similar groups. Perfect for SEO professionals, content strategists, and digital marketers.

## 🚀 Features

- Automatic keyword grouping using K-Means clustering
- TF-IDF vectorization for text analysis
- Easy-to-use Python script
- Export results to CSV

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation
- **Scikit-learn** - Machine learning algorithms
  - TF-IDF Vectorizer
  - K-Means Clustering

## 📂 Project Structure
```
keyword-clustering-ai/
│
├── data.csv              # Input keywords
├── clustering.py         # Main Python script
├── results.csv           # Clustered output
└── README.md            # Project documentation
```

## 🎯 How It Works

1. **Input**: Keywords in CSV format
2. **Processing**: 
   - Converts text to numerical vectors (TF-IDF)
   - Groups similar keywords using K-Means
3. **Output**: CSV file with cluster labels

## 💻 Installation & Usage

### Option 1: Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `data.csv`
3. Run the clustering code
4. Download `results.csv`

### Option 2: Local Setup
```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/keyword-clustering-ai.git
cd keyword-clustering-ai

# Install dependencies
pip install pandas scikit-learn

# Run the script
python clustering.py
```

## 📊 Sample Data

**Input (data.csv):**
```
keyword
buy shoes online
cheap shoes
running shoes
nike running shoes
best shoes for gym
```

**Output (results.csv):**
```
keyword,cluster
buy shoes online,0
cheap shoes,0
running shoes,1
nike running shoes,1
best shoes for gym,1
```

## 🔧 Customization

Change the number of clusters in `clustering.py`:
```python
kmeans = KMeans(n_clusters=3, random_state=0)  # Change 2 to any number
```

## 🎓 What I Learned

- Machine learning fundamentals
- Text vectorization with TF-IDF
- K-Means clustering algorithm
- Python data science libraries
- Combining SEO with AI

## 📈 Future Improvements

- [ ] Add automatic optimal cluster detection
- [ ] Create web interface
- [ ] Support for larger datasets
- [ ] Visualization of clusters
- [ ] Export to multiple formats

## 👤 Author

**Your Name**
- GitHub: [@goswamipriya](https://github.com/goswamipriya)
- LinkedIn: [Priya Goswami](https://www.linkedin.com/in/priyagoswami-seomanager/)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- First AI/ML project combining SEO + Python
- Built as part of learning data science

---

⭐ **Star this repo if you found it helpful!**
