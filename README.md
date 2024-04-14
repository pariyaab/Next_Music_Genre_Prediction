# Music Genre Prediction for Mental Health Analysis on Twitter

This project investigates the relationship between music listening patterns and mental health using a Twitter dataset. It explores the potential to predict the next music genre a user might be interested in, considering their:

    Mental health diagnosis: Categorized into a specific number of groups: depression, ptsd, anxiety, bipolar
    Music listening history: Shared music preferences and listening habits gleaned from their Twitter activity.

## Objective:

The primary objective is to leverage sequential models like LSTMs and GRUs to predict the next music genre of interest for users based on their mental health diagnosis and Twitter-derived music listening history.

Methodology:

    Data Acquisition and Preprocessing:
        A Twitter dataset containing user tweets and associated mental health diagnoses (categorized into groups).
        Preprocessing steps involved data cleaning and retreieving genres of the musics and preproceesed them.

    Model Development:
        Exploration of sequential models, such as LSTMs (Long Short-Term Memory) and GRUs (Gated Recurrent Units) for music genre prediction.
        Model training and hyperparameter tuning to optimize performance.

    Evaluation:
        Employing standard evaluation metrics like accuracy to assess model performance in predicting music genre based on mental health diagnosis and music listening history.

    Visualization and Analysis:
        Utilizing techniques like t-SNE to visualize the distribution of music genres within different mental health diagnostic groups.
        Analyzing the results to understand the relationships between music preferences, mental health, and the effectiveness of the prediction models.

Expected Outcomes:

    Develop a model that can predict the next music genre a user might be interested in based on their mental health diagnosis and Twitter-derived music listening history.
    Gain insights into the potential connections between music preferences and mental health.

Project Structure:
    models/: Folder containing the implemented models (LSTM, GRU etc.) and their training scripts.
    evaluation/: Folder containing scripts for model evaluation and relevant metrics.
    visualization/: Folder containing code for visualizations like t-SNE plots.
    notebooks/: Optional folder for Jupyter notebooks used for exploratory analysis and data visualization.
    README.md: This file (you are reading it!).

Note: Due to ethical considerations and privacy concerns, the Twitter dataset with individual user information is not included in this repository. You may need to acquire your own data or consider using a publicly available anonymized dataset.

Future Work:

    Explore the use of additional features beyond music listening history to enhance prediction accuracy.
    Investigate the incorporation of sentiment analysis from user tweets to further understand the emotional connection to music choices.
    Evaluate the potential for music recommendations tailored to mental health well-being based on user preferences and diagnoses (while adhering to ethical considerations).

Feel free to contribute!

This project is open-source, and contributions are welcome. If you have suggestions for improvements, bug fixes, or new functionalities, please consider submitting a pull request.
