# Customer-Reviews-Classification

Introduction:

We used two Fashion Datasets for this project that included the Reviews of different customers at Stylo (a fashion company). The datasets, named ‘Google_Reviews’ and ‘NPS_Reviews’, are attached. We used both Supervised and Unsupervised approaches. The goal was to classify reviews as Actionable and Non-Actionable and then further classify the Actionable into different categories and identify the department that they should be forwarded to. Our final selected approach was similarity-based classification (unsupervised) since it was simple and yet produced pretty good results.

Following is the list of approaches we tried in each step of the overall project implementation:

1. Pre-processing:
   
    Removing Nulls
   
    Removing Spaces
   
    Removing incomplete words
   
3. Embeddings:
   
    GloVe
   
    Vader with mini-LM
   
    HuggingFace transformers
   
5. Evaluation:
   
    For supervised: accuracy, precision, recall, F1 score
   
    For unsupervised: Visually analyzing the results
   
7. Supervised Classification:
   
    Bayes
   
    Deep Learning NN
   
9. Unsupervised Classification:
    
    RAG based
   
    Similarity based

Installation Instructions:

The notbooks can be run seperately, as long as the datasets are both in the same direcotry and the requirements are satisfied.

Usage Guide:
The notebook 'Supervised_Approaches' includes all the supervised approaches initially tried for Action recognition by analyzing sentiments. The notebooks 'Unsupervised_RAG_based_approach' and 'Unsupervised_Similarity_based_approach' cover both action recognition and classification into different categories. The 'Unsupervised_Similarity_based_approach' also includes the Gradio interfaces since this was our best approach. 

Results and Visuals:
![06e270fc-c425-4c76-be82-2c050f3496fe](https://github.com/user-attachments/assets/d4dcdd2b-1f79-4b5c-8538-34e2274cf740)
![fdf776ec-a286-4a34-81f8-79e0e54463fc](https://github.com/user-attachments/assets/fbc068b0-2542-44f6-8a1e-d3f888b18a54)
![70ff1655-d48b-4c3b-b8f9-be30dd1a2093](https://github.com/user-attachments/assets/3b7c5cc4-206a-4e7f-a87c-20461b0a2a85)


License Information:
No Licences applied.

