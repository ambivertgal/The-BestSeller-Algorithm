# The BestSeller Algorithm

A comprehensive data science project that analyzes book reviews and ratings to uncover patterns in reader preferences and book popularity using advanced text analysis and topic modeling techniques.

##  Project Overview

This project explores how reader-generated data from platforms like Hardcover can be used to uncover meaningful patterns in book genre popularity. With a growing volume of public reviews and ratings available online, publishers can complement traditional market research with data-driven insights to better understand reader preferences and market trends.

##  Project Objectives

- **Data Acquisition**: Collect comprehensive book metadata and user reviews from the Hardcover platform
- **Text Analysis**: Analyze review content to understand reader sentiment and preferences
- **Topic Modeling**: Identify dominant themes and topics in book reviews using advanced NLP techniques
- **Genre Analysis**: Explore patterns across different book genres and their popularity
- **Sentiment Analysis**: Understand the emotional tone of reviews and its correlation with ratings

## Project Structure

```
The-BestSeller-Algorithm/
├── Part1_Data_Acquisition.ipynb          # Data collection and preprocessing
├── Part2_TextAnalysis_TopicModelling.ipynb # Text analysis and topic modeling
├── annotated-BUDT758J_Final%20Project%20Report.pdf  # Final project report
└── README.md                             # This file
```

##  Methodology

### Part 1: Data Acquisition
- **Web Scraping**: Collected book metadata and reviews from Hardcover platform
- **Data Processing**: Cleaned and structured the collected data
- **Dataset Creation**: Built a comprehensive dataset with book details and user reviews

### Part 2: Text Analysis & Topic Modeling
- **Text Preprocessing**: Applied spaCy-based lemmatization and filtering
- **Word Cloud Analysis**: Generated visualizations for overall and sentiment-specific word frequencies
- **Sentiment Analysis**: Used VADER sentiment analyzer to classify reviews as positive, negative, or neutral
- **Topic Modeling**: Implemented BERTopic with Sentence Transformers, UMAP, and HDBSCAN
- **Genre Mapping**: Mapped topics to book genres to understand thematic patterns

##  Key Findings

### Sentiment Distribution
- **69%** of reviews were classified as positive
- **17%** of reviews were classified as negative  
- **12%** of reviews were classified as neutral

### Topic Modeling Results
- Successfully identified **141 distinct topics** from the review corpus
- Topics covered various themes including character development, plot structure, emotional impact, and genre-specific elements
- Multilingual content was detected, including Spanish and Dutch reviews

### Genre Analysis
- Found significant topic diversity across different genres
- Romance and Fiction genres exhibited the highest topic diversity
- Each genre showed distinct thematic patterns in reader discussions

##  Technologies Used

### Data Collection & Processing
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **BeautifulSoup/Requests**: Web scraping
- **spaCy**: Text preprocessing and lemmatization

### Text Analysis & NLP
- **VADER**: Sentiment analysis
- **WordCloud**: Text visualization
- **BERTopic**: Advanced topic modeling
- **Sentence Transformers**: Text embeddings
- **UMAP**: Dimensionality reduction
- **HDBSCAN**: Clustering

### Visualization & Analysis
- **Matplotlib**: Data visualization
- **Plotly**: Interactive visualizations
- **Jupyter Notebooks**: Development environment

##  Dataset Information

The project analyzes a comprehensive dataset containing:
- **21,515 book reviews** from Hardcover platform
- **300 unique books** across various genres
- **282 different genres** represented
- **Multilingual content** including English, Spanish, and Dutch reviews

##  Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebooks
- Required Python packages (see installation below)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/The-BestSeller-Algorithm.git
cd The-BestSeller-Algorithm
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib plotly
pip install spacy vaderSentiment wordcloud
pip install bertopic sentence-transformers umap-learn hdbscan
pip install beautifulsoup4 requests
```

3. Download spaCy model:
```bash
python -m spacy download en_core_web_sm
```

### Running the Analysis

1. **Data Acquisition** (Part 1):
   - Open `Part1_Data_Acquisition.ipynb`
   - Run cells sequentially to collect and process data
   - Output: Cleaned dataset ready for analysis

2. **Text Analysis & Topic Modeling** (Part 2):
   - Open `Part2_TextAnalysis_TopicModelling.ipynb`
   - Execute cells to perform sentiment analysis and topic modeling
   - Generate visualizations and insights

##  Key Features

- **Comprehensive Data Collection**: Automated web scraping from Hardcover platform
- **Advanced Text Processing**: Sophisticated NLP pipeline for review analysis
- **Sentiment Analysis**: Multi-level sentiment classification and visualization
- **Topic Modeling**: State-of-the-art BERTopic implementation for theme discovery
- **Genre Mapping**: Cross-reference topics with book genres for deeper insights
- **Visualization**: Rich set of charts and word clouds for data exploration

##  Analysis Components

### Word Cloud Analysis
- Overall review word frequency visualization
- Sentiment-specific word clouds (positive vs negative reviews)
- Filtered generic terms to highlight meaningful patterns

### Sentiment Analysis
- VADER-based sentiment scoring
- Three-way classification (positive, negative, neutral)
- Sentiment distribution analysis across genres

### Topic Modeling
- BERTopic implementation with advanced preprocessing
- 141 identified topics with representative documents
- Topic-genre mapping for thematic analysis
- Topic diversity analysis across genres

##  Results & Insights

The analysis revealed several key insights about reader behavior and preferences:

1. **Positive Bias**: Readers tend to share favorable experiences (69% positive reviews)
2. **Emotional Engagement**: Reviews are often emotionally charged and reflective
3. **Genre Diversity**: Different genres show distinct thematic patterns
4. **Multilingual Content**: Platform attracts diverse international readership
5. **Topic Richness**: 141 distinct topics indicate rich, varied reader discussions

##  Contributing

This is an academic research project. For questions or collaboration opportunities, please refer to the project report or contact the research team.

##  License

This project is for academic research purposes. Please respect the terms of use for any external data sources referenced in the analysis.

##  References

- Hardcover platform data (web scraping)
- BERTopic documentation and implementation
- VADER sentiment analysis methodology
- spaCy NLP framework

---

**Note**: This project demonstrates advanced data science techniques applied to literary analysis, providing valuable insights for publishers and researchers interested in understanding reader preferences and market trends. 
