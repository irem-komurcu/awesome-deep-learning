# Awesome Deep Learning

This repo is designed to provide a comprehensive and accessible introduction to Deep Learning. We will start by laying a solid foundation in the core concepts of Deep Learning, covering topics such as neural networks, activation functions, optimization algorithms, and regularization techniques. Building upon this foundation, we will explore advanced architectures, including convolutional neural networks (CNNs) for image analysis, recurrent neural networks (RNNs) for sequential data processing, and generative adversarial networks (GANs) for generating novel content.

To help you apply Deep Learning effectively, we will delve into practical considerations such as data preprocessing, model evaluation, and hyperparameter tuning. We will also discuss the ethical implications and challenges associated with Deep Learning, ensuring you understand the field holistically.

With this repo, you can find supplementary materials, code examples, and additional resources. Repo <b>will update with new titles and subjects</b>. I attribute this repo as <b>Version 0.1</b>

# Say Hi to Deep Learning

## Why Deep?
Deep Learning is a concept that has revolutionized the field of artificial intelligence and has gained popularity in recent years. Inspired by the working principles of the human brain, this approach uses multilayer artificial neural networks to solve complex problems and explore deep structures in data. So why is this approach called "deep," and why is it so important?

Deep Learning stands out with its ability to automatically learn high-level representations in data. This means it can represent data in a more meaningful way. Deep learning models analyze data layer by layer with operations in multi-layered neural networks and represent them at higher abstraction levels. In this way, essential features in the data are automatically discovered.

## Machine Learning Umbrella and Deep Learning Relationship
Machine learning and deep learning are two important concepts that have significantly impacted the fields of artificial intelligence and data analytics. While they are related, they are also distinct. Machine learning is a broader term encompassing deep learning, a subset of machine learning. Understanding the differences between machine learning and deep learning is crucial.

### Machine Learning
Machine learning is a branch of artificial intelligence that enables computer systems to improve by utilizing data. Its goal is to develop algorithms that can detect patterns and relationships to solve specific tasks or problems. Machine learning allows a model to learn from data-driven experiences and make predictions based on new data.

Machine learning includes various techniques such as supervised learning, unsupervised learning, and reinforcement learning.

- **Supervised Learning:** Labeled data is used to train the model in this approach. The model learns to associate input data with a specific output or class label. Examples of supervised learning tasks include handwriting recognition or email spam filtering.
- **Unsupervised Learning:** Unlabeled data is used in this approach. The model attempts to discover structures or hidden patterns in the data. Examples of unsupervised learning tasks include clustering based on similar features or dimensionality reduction.
- **Reinforcement Learning:** In this approach, an agent learns to achieve a specific goal by interacting with its environment. The model learns to make the correct decisions based on feedback received from the environment. Examples of reinforcement learning tasks include learning strategies for playing games or robot control.

Machine learning algorithms involve essential stages such as feature engineering, model selection, and hyperparameter tuning. During these stages, thoroughly examining the dataset, preprocessing steps, and proper model training is necessary.

### Deep Learning
Deep learning is a **subset of machine learning** that utilizes artificial neural networks to solve complex problems. It focuses on **solving complex problems** using models consisting of multiple layers of neural networks. Deep learning models learn high-level representations from the data, automatically performing feature engineering.

Deep learning differs from traditional machine learning methods in several ways:

1. **Feature Learning:** In traditional machine learning methods, feature engineering is performed to manually extract features from the dataset. Deep learning, on the other hand, learns features automatically. This requires less human intervention and can discover more complex features.
2. **Data Representations:** Deep learning models learn high-level representations of the data through operations in multi-layered neural networks. These representations enable more meaningful data representation and enhance the model's performance.
3. **Computational Power:** Deep learning models often require larger computational resources to perform well on large datasets and complex problems. Therefore, deep learning typically demands more computational power.

Machine learning and deep learning often need clarification because deep learning is a subset of machine learning. However, deep learning is a more specialized and complex field requiring more computational power and data. Additionally, deep learning is commonly applied in high-dimensional datasets and complex data types such as images, audio, or natural language processing tasks. In contrast, machine learning can be applied to a broader range of data types and tasks.

### Where is Data Science in this?

I wrote a Medium Blog about Data Science hierarchy. This blog contains Data Science’s working areas.

[Data Science and Data Science Hierarchy](https://heartbeat.comet.ml/data-science-and-data-science-hierarchy-4e7a5b924184)

Data Science can be defined as a field where disciplines such as data analytics, statistics, machine learning, and data exploration are combined. Analyzing data, revealing exploratory information by modeling, and making data-based decisions are the main goals of Data Science. Deep Learning is an essential component within this broad field.

Deep Learning plays an essential role in Data Science. Data Science often resorts to deep learning methods to analyze complex structures in large data sets and obtain data-driven results. Deep Learning automatically learns high-level representations in data using models composed of multi-layered neural networks. This provides the ability to discover essential features in data and model complex relationships.

# AI Interviews
The processes are different in all the interviews I have attended, but the questions and general requests are similar.

While some companies start with an HR phase/behavioral and continue with a technical interview and take-home-assignment phase, some start with a direct technical interview and then continue with an HR interview. There are recruitment processes consisting of 6 stages; there are also recruitment processes that end in 1 or 2 stages. Only some companies send a take-home-assignment. Some companies prefer live coding instead of sending take-home assignments.

****A seemingly easy question: Can you tell me a little about yourself?****

The first question in all the interviews I attended was, “Can you tell me a little about yourself.” Sounds easy, right? I can say that this question determines the course of the whole interview.

I'd like to point out that interview questions develop depending on your previous experience. What are your areas of interest? Did you launch a project on this subject? How many people did you work with, what programming language/framework did you use, is the project live now, etc? This is the first stage of the interview.

In other words, the key information you provide in the part where you describe yourself and what you have done can determine other questions to come.

Make a confident introduction in the part about yourself, try to explain in technical terms while talking about your projects, and explain in a fluent and non-confusing way.

I have seen that your command of the subject you describe, owning past projects, and your work are essential in creating a good impression at the first stage. I would also like to point this out.

## **Technical Interview Questions**

In the first part of the technical questions, I received questions about the technical parts of the projects. I explained in the question, “Can you tell me a little about yourself” above. It would be best if you were realistic in your projects, and you can remain confident that questions will come from here.

For example, I applied for a company that only deals with structured data and interviewed for the Data Scientist position. Many Computer Vision questions were asked because my previous projects were based on computer vision. Even if I didn’t deal with Computer Vision there, I’m sure they were asking me to test the accuracy of what I said.

In all the interviews, there were many questions about whether I understood the math of the job or not. Much more than the questions I’ve listed below have been asked in different scenarios, in easy-to-hard ways. Therefore, I would say that you should research the questions I have listed below in more detail. I list some sample questions below;

- Why don’t we use the Relu activation function in the output layer?
- We have a scenario like this; according to this scenario, which activation function would you prefer in the output layer? Why?
- Which metrics did you use in your projects?
- Can you distinguish between Precision, Recall, and F1 Score? What are the differences? What metrics would you use in the XXX scenario?
- What is dropout? How is the output affected when a dropout is always applied to the same value?
- How does our Confusion Matrix change when we increase the threshold from 50% to 80%?
- Do you know ML/DL algorithms? (You are not expected to know all the algorithms in this section, but knowing the basic algorithms, mainly, earns plus points. I received questions about algorithms such as PCA, K-Means, SVM, Decision Tree, and XGBoost)
- Optimization algorithm selection and optimization logic
- Have you worked with pre-trained models before? Which ones did you use? How did it benefit your output?
- What is transfer learning? Have you been able to use it before?
- What is Augmentation? What augmentation techniques would you use in a scenario where our goal is XXX?
- Which frameworks did you use? For example, do you know the tf.record, tf.data features for Tensorflow, and how did you use them?
- What is normalization, and what are normalization techniques? Why do we use normalization?
- What is overfitting-underfitting, and when does it occur? How would you intervene? (These questions sometimes come directly without saying overfitting-underfitting. For example, they can be asked with scenarios such as this much success in the train data but this much success in the test dataset)
- How would you separate the test and train dataset? Why is the validation dataset necessary?
- What is cross-validation?
- What is regularization, the differences between the techniques, and in which situations is it used?
- Recommendation systems and system scenario questions

**Python, R, SQL, and more**

Python is an essential programming language for Data Scientist positions. If you can read the data, can you actively use Numpy, Pandas, and Scikitlearn libraries to answer and analyze their questions?

*You can find the article where [I listed the resources for the Python programming language here](https://iremkomurcu.medium.com/python-%C3%B6%C4%9Frenenler-i%CC%87%C3%A7in-kaynak-%C3%B6nerileri-82485fa07e0e).* [TR]

![Python Öğrenenler İçin Kaynak Önerileri](https://github.com/irem-komurcu/awesome-deep-learning/blob/main/media/python_ogrenenler_%C4%B1c%C4%B1n_kaynak_onerileri.png)

Reading, analyzing, shaping, and preprocessing data is very important for Data Science. That’s why it is a default request to understand various data with the programming language.

Although SQL is not asked in every interview, it is a required skill from time to time in Data Science positions. Your job may fall into SQL in data science, so be prepared for SQL experience questions that may come in the interview.

R is a programming language not asked because I have no experience, but it came up in Data Science interviews.

*You can find my article here, where [I list the resources you can use to learn programming languages and](https://iremkomurcu.medium.com/algoritma-ve-programlama-dili-%C3%B6%C4%9Frenenler-i%C3%A7in-kaynak-%C3%B6nerileri-29a66d34dfee) improve your algorithm skills.* [TR]

![Algoritma ve Programlama Dili Öğrenenler için Kaynak Önerileri](https://github.com/irem-komurcu/awesome-deep-learning/blob/main/media/algoritma_ve_programlama_dili_ogrenenler_icin_kaynak_onerileri.png)

**Cloud Experience: Google Cloud, AWS, and more**

Cloud experience was a subject that I mentioned during my application, which is also on my CV and which put me a few steps ahead in the interviews.

In Data Science studies, work is mainly done on the cloud, not locally, for data density, model complexity, and installation costs. Therefore, having a good command of working with notebooks, knowing Anaconda products, and having information about Cloud technologies' services is essential. Most of the time, using Cloud tools rather than rewriting a project significantly reduces costs. Cloud products are very useful not only in terms of hardware but also in terms of tools.

Therefore, entering Data Science interviews with knowledge of Cloud products and experience will put you ahead.

**Unexpected Questions**

There were also problem-solving questions in the interview. In addition to the opposite questions on the technical side, some questions measure your analysis skills and way of thinking. In such questions, thinking aloud, commenting, and attributing what you say to a reason is essential.

- How many families with children are there in Istanbul?
- How many liters of olive oil is used annually in France?
- If we have eight balls and a balance board, and only one is heavier, how many ways can we balance the heavy ball with the balance board?
- How much shampoo is consumed in a year in the world?

I’m sure the questions were surprising for you too. Do not forget that the purpose of asking these questions is to evaluate and analyze different situations, which is one of the important competencies of Data Science, and accordingly, answering the problem in each question using data vernacular will earn you plus points.

For example, the question of shampoo usage rate; How many times a week do you shower on average, and how often you use how many liters of shampoo can be a good introduction. Thinking out loud about details and expressing abnormal and different situations by looking at the data will have a positive effect, such as people who use soap instead of shampoo, people with long hair shampoo their hair 2–3 times in a single shower, people who do not have hair will not use one or no shampoo at all.




