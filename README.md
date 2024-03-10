Project Description: COVID-19 Chatbot with Information Retrieval

Overview:
This project aims to develop a chatbot named Lisa that can provide information and answer queries related to COVID-19. Lisa retrieves information from an article sourced from Britannica's website and utilizes natural language processing techniques to respond to user queries.

Key Components:
1. Web Scraping and Article Extraction: Lisa uses the Newspaper3k library to scrape an article from the provided URL. The article is then parsed, and its text content is extracted for further processing.

2. Text Preprocessing: The extracted text undergoes preprocessing steps, including tokenization into sentences and removal of punctuation. This ensures that the text is in a suitable format for analysis and response generation.

3. Response Generation: Lisa generates responses to user queries by computing the cosine similarity between the user's query and sentences from the extracted article. The response is based on the sentence most similar to the user's query, providing relevant information about COVID-19.

4. Greeting Functionality: Lisa is programmed to greet users and respond to common greetings such as "hi," "hello," or "hey." This adds a friendly and conversational aspect to the interaction.

5. User Interaction: Users can interact with Lisa by inputting queries related to COVID-19. Lisa processes the queries, retrieves relevant information from the article, and provides informative responses to the users.

 Implementation Details:
1. Text Processing: The NLTK library is utilized for text processing tasks such as tokenization, stemming, and stop word removal. These techniques help in preparing the text data for analysis and response generation.

2. Vectorization and Similarity Calculation: Lisa employs TF-IDF vectorization to convert text data into numerical vectors, enabling the calculation of cosine similarity between user queries and sentences from the article. This allows Lisa to identify the most relevant information to provide to the users.

3. Chatbot Interaction: Lisa initiates interaction with users by asking for queries related to COVID-19. Users can input questions or seek information, and Lisa responds accordingly with informative answers sourced from the article.

Conclusion:
Through this project, Lisa serves as a helpful resource for users seeking information about COVID-19. By leveraging web scraping, natural language processing, and cosine similarity calculations, Lisa retrieves and provides relevant information from an article, offering users a convenient and accessible means of accessing COVID-19-related information. This chatbot can be further enhanced with additional features and functionalities to improve its usability and effectiveness in addressing user queries and concerns related to the pandemic.
