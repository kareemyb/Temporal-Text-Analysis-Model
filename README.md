# Temporal Text Analysis Model for Black History Media Documents

## Overview
The Temporal Text Analysis Model is a sophisticated tool designed to uncover and analyze historical trends within Black history, focusing specifically on the realm of media documents. This model delves deep into the evolution of discussions, perceptions, and the significance attributed to historical events, figures, and cultural developments over time. By examining a vast corpus of historical media documents, the model offers invaluable insights into the changing landscape of Black history as portrayed in media.

## Objective
The primary goal of this model is to provide a granular, time-oriented analysis of how Black history has been represented and perceived in historical media documents. This analysis includes identifying predominant themes, sentiment trends, and the frequency and context of discussions around significant events and figures.

## Features
- **Data Loading and Preprocessing**: The model begins by loading and preprocessing historical documents, ensuring they are in a suitable format for analysis.
- **Sentiment Analysis**: Utilizing the TextBlob library, the model evaluates the sentiment of each document, providing a quantitative measure of the document's tone.
- **Topic Modeling**: Leveraging Latent Dirichlet Allocation (LDA), the model identifies and categorizes predominant themes within the data, offering insights into the main topics of discussion across different time periods.
- **Time-Series Analysis**: The model includes a comprehensive time-series analysis, tracing the evolution of sentiments and topics over time, highlighting how perceptions and discussions have shifted.

## Usage
The Temporal Text Analysis Model is encapsulated within a Jupyter Notebook, making it accessible and easy to use for individuals with varying levels of technical expertise. Users can interact with the notebook to load new data sets, adjust parameters for sentiment analysis and topic modeling, and visualize the results through time-series graphs.

## Installation
1. Clone the repository or download the Jupyter Notebook.
2. Ensure you have Python installed, along with the following libraries: `pandas`, `numpy`, `spacy`, `sklearn`, `matplotlib`, `seaborn`, and `textblob`.
3. Open the notebook in Jupyter Lab or Jupyter Notebook interface and execute the cells sequentially.

## Data Format
The model expects input data in RTF format, containing historical media documents. Each document should be textually rich and ideally annotated with the date or period it pertains to for accurate temporal analysis.

## Outputs
- **Sentiment Over Time**: A line graph showcasing how the sentiment within the media documents has evolved over the selected timeframe.
- **Topic Distribution**: A stacked bar chart illustrating the prevalence of different topics over time, providing a visual representation of shifting focus areas within the media.

## Future Enhancements
- Integration with more advanced NLP models for nuanced sentiment and context analysis.
- Expansion of the topic modeling component to include dynamic topic modeling, capturing the evolution of topics more fluidly.
- Incorporation of user interaction within the chatbot interface, allowing users to query specific time periods, events, or figures.

## Contribution
Contributions are welcome! If you have suggestions for improving the model or extending its capabilities, please feel free to fork the repository, make your changes, and submit a pull request.

## License
This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
