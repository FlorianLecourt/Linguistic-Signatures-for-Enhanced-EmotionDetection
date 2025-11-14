# Linguistic Signatures for Enhanced EmotionDetection

Github repository containing the trained models and results linked to the paper **Linguistic Signatures for Enhanced EmotionDetection**.

## Description

The RoBERTA-based models are stored in **Models**, alongside a summary of the evaluation metrics per seeds, the training loss curves, boxplots plotting the evaluation differences between the seeds, and one folder per seeds containing:
+ *pytorch_model.bin*, the RoBERTa-based model
+ *metrics.csv*, the F1 score per class
+ *results.csv*, the evaluated GoEmotions texts, the true labels and the predicted labels
The Prompts (0 shot and 1 shot) sent to LLama3.2, with the LLM's responses are also available in **Models**.

The linguistics signatures are stored in **Signatures** in a txt file, sorted by datasets and per emotion labels in said dataset. A pie chart representation is also available in **Signatures PieCharts**. Similar to **Signatures PieCharts**, **Histograms** store the linguistic signatures, sorted by datasets and per emotion labels, but this time represented by bar charts like a histogram.

The 30 emotions set, alongside their GI Features are available in **Emotion Comparisons**.

## Getting Started

### Dependencies

* Python 3.11
    + datasets 3.6.0
    + matplotlib 3.10.3
    + numpy 2.2.5
    + pandas 2.2.3
    + pillow 11.2.1
    + scikit-learn 1.6.1
    + seaborn 0.13.2
    + torch 2.7.0
    + tqdm 4.67.1
    + transformers 4.51.3

## License

This project is licensed under the [???] License 

## Acknowledgments

This research was supported by the European Regional Development Fund (FEDER) through the IA-EMOTION project.