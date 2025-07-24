# nlp-summarization-project
An NLP project for extractive document summarization using TextRank and TF-IDF.
# Automating Document Summarization for Information Overload

This project develops an automated extractive document summarization system designed to combat information overload by processing raw news articles into concise summaries.

## Key Features / Approach
- Extractive Summarization: Implemented a TextRank-like algorithm to identify and extract the most important sentences from a document.
- TF-IDF & Cosine Similarity: Utilized TF-IDF vectorization to represent sentences and cosine similarity to measure sentence relationships.
- PageRank Algorithm: Applied the PageRank algorithm (from NetworkX) on a sentence similarity graph to rank sentences by importance.
- Data Preprocessing: Developed robust text cleaning pipelines using regular expressions.
- Parameter Tuning: Explored and optimized summarization output by adjusting parameters such as `top_n` sentences and `ngram_range`.
- Performance Evaluation: Included metrics like True Positives, False Positives, and False Negatives to assess summarization quality.
- Visualization: Generated heatmaps of sentence similarity matrices for insightful analysis.

## Technologies Used
- Python
- Pandas (for data handling)
- Scikit-learn (TF-IDF, Cosine Similarity)
- NetworkX (PageRank implementation)
- Matplotlib, Seaborn (for visualizations)
- Regular Expressions (for text cleaning)

## How to Run (Optional - if you want to provide instructions)
1. Clone this repository: `git clone [your_repo_link]`
2. Navigate to the project directory.
3. Install dependencies: `pip install pandas scikit-learn networkx matplotlib seaborn`
4. Open the Jupyter Notebook/Google Colab file: `your_notebook_name.ipynb`
5. Run all cells.

## Files
- `your_notebook_name.ipynb`: The main Google Colab notebook containing all the code.
- `news_summary.csv`: The dataset used for summarization.
