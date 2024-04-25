
# 🤖 End-to-End Text Summarizer

This project is an end-to-end text summarizer that uses modular coding, a pipeline architecture, and the Google Pegasus model. It is trained on the SAMSUM corpus and uses ROUGE as an evaluation metric. The summarizer is deployed via Flask.







## Screenshots

![Screenshot 1](https://github.com/bhaveshk22/Text_Summarizer/assets/141263853/5cc450d5-1ca5-4fd9-97b1-2adbc120bc81)


![Screenshot 3](https://github.com/bhaveshk22/Text_Summarizer/assets/141263853/a956c342-40a8-4417-8de8-58301ea91ecb)





## Roadmap

The project uses a pipeline architecture, that means the system is divided into several stages that are executed in a sequence. The pipeline includes the following stages:

- **Data Ingestion**: In this stage, data is downloaded from the source and stored by creating a directory.
- **Data Validation**: This stage involves checking the data for errors or invalid format.
- **Data Transformation**: In this stage, the data is transformed into a format that can be used by the model.
- **Model Trainer**: In this stage, the model is trained using the transformed data. The training process involves optimizing the model's parameters to minimize the loss function and improve the model's performance.
- **Model Evaluation**: In this stage, the model is evaluated using mertrics like ROUGE. 
- **Summary Generation**: In this stage, the model is used to generate summaries for new input text. 

## Model
The project uses the Google Pegasus model, which is a state-of-the-art model for text summarization. Pegasus is a pre-trained transformer model that is fine-tuned for summarization tasks. It is designed to generate high-quality summaries that are coherent, fluent, and informative.

## Trained on SAMSUM Corpus
The project is trained on the SAMSUM corpus, which is a dataset of human-written conversations between two speakers. The corpus contains 16,336 dialogues and 347,791 utterances. The dataset is used to train the Pegasus model for summarization tasks.

## Evaluation Metrics
The project uses ROUGE as an evaluation metric to measure the quality of the summaries. ROUGE is a set of metrics that measure the overlap between the generated summary and the reference summary. It includes ROUGE-1, ROUGE-2, and ROUGE-L, which measure the overlap of unigrams, bigrams, and longest common subsequences, respectively.

## Deployed via Flask
The project is deployed via Flask, which is a lightweight web framework for building web applications in Python. Flask provides a simple and flexible way to expose the summarizer as a web service, allowing users to input text and receive a summary as a response.



## Lessons Learned

During the development of the text summarizer project, I learned several key lessons:

- **Data Quality**: High-quality data is critical for model performance. Invest time in data validation and cleaning.
- **Model Training**: Careful tuning of hyperparameters can significantly improve model performance.
- **Evaluation Metrics**: Evaluation metrics like ROUGE scores are essential for model selection.

These lessons will be valuable for future projects and will help me continue improving my skills and expertise in natural language processing.


## Getting Started

Clone the project

```bash
  git clone https://github.com/bhaveshk22/Text_Summarizer.git
```

Go to the project directory

```bash
  cd Text_Summarizer
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Train the model

```bash
    python main.py
```

Start the server

```bash
  python app.py
```


## Workflow
1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update configuration manager at src config
5. Update conponents
6. Update pipeline
7. Update main.py
8. Update app.py
## Authors

- [@bhavesh](https://github.com/bhaveshk22)


# Hi, I'm Bhavesh! 👋


## 🚀 About Me
I'm a Full Stack Data Scientist


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhavesh-kabdwal-6ba30a25b)


## 🛠 Skills
1. C, C++, Python
2. SQL
3. Machine Learning
4. Deep Learning
5. Data Science


## Summary of My Journey
👩‍💻 I'm currently a student

🧠 Btech Computer Science

💬 more details loading

![Logo](https://github-readme-stats.vercel.app/api?username=bhaveshk22&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=151515)

