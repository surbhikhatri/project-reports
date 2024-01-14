# project-reports
1. Portable Physician:
    Biomedical text mining is becoming increasingly important as the number of biomedical
    documents rapidly grows. With the progress in natural language processing (NLP),
    extracting valuable information from biomedical literature has gained popularity among
    researchers, and deep learning has boosted the development of effective biomedical text
    mining models. However, directly applying the advancements in NLP to biomedical text
    mining often yields unsatisfactory results due to a word distribution shift from general
    domain corpora to biomedical corpora. Here we investigate how the recently introduced
    pre-trained language model BERT can be adapted for biomedical corpora.
    Results: We developed our project which uses Bidirectional Encoder Representations from
    Transformers for Biomedical Text Mining, which is a domain-specific language
    representation model pre-trained on large-scale biomedical corpora. Our analysis results
    show that pre-training BERT on biomedical corpora helps it to understand complex
    biomedical texts. Which can be used to give answers to simple queries. We made an
    application which can take input in native language like Hindi, Marathi, Tamil, Telugu etc
    from the user of the application and and respond back to user according to his/her
    symptoms in the same language.

2. Global Automation Search (VMWare Internship Report):
    As searching of internal documents very frequently. Looking at current scenario the data is growing day by day which makes the searching slow. It is problematic now and going to be even more problematic in the future to search for the growing data. Slower results makes users impatient and also reduces productivity. Also to make it more user friendly, the search engine should have substring search and also incorporate natural language queries. So it is decided to handle this problems in two parts, first to index all the data we have for faster search and then applying NLP to get relevant results for natural language queries. Hence, we aim to make searching experience awesome by backing it with an appropriate search engine that deals with natural language queries.
    For indexing the data, the project uses Elasticsearch which is a open source search and analytics engine and can store unlimited records free of cost. For NLP it uses Naïve Bayes algorithm and train the dataset using NLTK library for python which provides many complicated functionalities to be used directly. It uses Flask for backend and Angular for UI
    Results: A flask project is created which has two major use cases first being to index all the data and provide autocomplete feature and second is to apply NLP for better search experience.

3. Logo Detector: 
    Objective: To provide Brand Detection as a Service. To build a Deep learning tool to find brand logos in everyday pictures. To build a general-purpose logo detection Software. To avoid re-training the network for each new company using the service, we divide logo detection and identification in two logically and operationally separate parts: To find all logos in the image with a YOLO detector (using the Keras implementation of keras-yolo3).To check for similarity between the proposed logos and an input uploaded by the customer. To implement few shot learning on new logos without re-training the model again. Results and Recommendation:The logo Detection software has been developed and tested successfully on random images. It properly detected the possible logo containing regions and then correctly classified the detected logo. Thus it is working properly . Recommendation for the future scope of this unit is to train it on even larger data set to get further more accurate results and can use special zooming cameras which can be used to detect logos from a considerable distance too. We can also extend the problem statement to detect the if the logo in the image is original or fake.
