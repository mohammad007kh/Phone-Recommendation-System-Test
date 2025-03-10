# Phone Recommendation System

This notebook demonstrates a machine learning project to build a phone recommendation system using a dataset of items and reviews. We go through the steps of loading the data, preprocessing, building the recommendation system, and evaluating the results.

## Dataset
- **Name**: `items.csv` and `reviews.csv`
- **Description**: The dataset contains information about phone items and user reviews. The goal is to recommend phones based on content and collaborative filtering.

## Project Steps
1. **Data Preprocessing**: Handle missing values and combine text features for better representation.
2. **Feature Extraction**: Convert text data into numerical features using TF-IDF Vectorization.
3. **Compute Cosine Similarity**: Measure the similarity between items using cosine similarity.
4. **Build the Recommendation System**: Develop a content-based recommendation system.
   - **Algorithms Used**: TF-IDF, Cosine Similarity
5. **Hybrid Recommendation System**: Combine content-based and collaborative filtering methods.
6. **Evaluation**: Evaluate the recommendation system using precision and recall.
   - **Evaluation Metrics**: Precision, Recall

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/Phone-Recommendation-System.git
cd Phone-Recommendation-System
pip install -r requirements.txt
```

## Usage

Each project is contained within its own directory. Navigate to the project directory and follow the instructions in the respective README files to run the project.

## Contributing

Contributions are welcome!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.