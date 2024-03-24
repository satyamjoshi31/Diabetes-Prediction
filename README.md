# Diabetes-Prediction
A Data Science Project to predict if a person has diabetes based on certain health parameters. This project implements column transformers, pipeline building and model serialization and deserialization.
Here, after loading dataset and performing basic EDA and data cleaning, I have created column transformers for one hot encoding, standardizing the data, and RandomForestClassifier model. Then all these transformers are pipelined.
The pipeline object is then serialized to a pkl file and in a different colab file, the pkl file is loaded and examined on random user inputs.
