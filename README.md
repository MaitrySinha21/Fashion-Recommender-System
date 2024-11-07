# Fashion_Recommender_System

## This project is a state-of-the-art image recommender system that uses 'order_id' to generate and manage embeddings.This recommender system is it is recommending images from web URL. So, no need to save any extra image in the local machine , which is saving a lot of memory & space, making it exceptionally memory-efficient and scalable for real-time recommendations.

## Dataset & Preprocessing:-

## Using a large dataset from Myntra, each product was assigned an order_id, which allowed our system to locate and retrieve the same product from Myntra’s website. We used this feature to generate embeddings for each product in the dataset, capturing essential visual characteristics that define its style. Additionally, our system dynamically fetches similar products directly from Myntra, generating embeddings on-the-fly for comparison, which eliminates the need for saving extra images locally.

## Architecture, Tools, & Libraries Used:

**Python: Core language for development.**

**DenseNet121: A pre-trained deep learning model in TensorFlow, chosen for its efficiency in capturing complex visual features for embedding generation.**

**TensorFlow: Framework for building, training, and fine-tuning DenseNet121 on our cleaned dataset.**

**K-Nearest Neighbors (KNN) Classifier: Used to identify and recommend similar images by comparing embeddings.**

**OpenCV: For image processing tasks, such as resizing and normalization.**

**HTML, CSS, JavaScript: For creating a responsive and intuitive web-based user interface.**

**Pipeline Design & Efficiency: To optimize performance, we created a robust pipeline that integrates data cleaning, embedding generation, and recommendation efficiently. By using DenseNet121 embeddings and KNN, we can quickly compute similarities between images based on web URLs, avoiding the need for local storage of images and saving significant memory and storage space.**

## Key Learnings:
**Data Cleaning: High-quality data is crucial for building accurate recommendation systems. Through this project, we learned how important data cleaning and preprocessing are for enhancing model performance and reducing noise.**

**Efficient Memory Management: By directly recommending images from web URLs, we achieved a highly memory-efficient solution, making the system scalable and cost-effective.**

**Pipeline Creation: Developing an end-to-end pipeline taught us the value of modular design, enabling quick adjustments to the system’s components without affecting the whole project.**

**Advanced Similarity Search: Using embeddings instead of raw images allowed us to perform rapid, accurate similarity searches with minimal computational load.**
 
 #### Output-
 ![fashion](https://user-images.githubusercontent.com/85226862/177802142-9b1d5740-b0b2-4131-986d-2f586417edda.gif)

 



