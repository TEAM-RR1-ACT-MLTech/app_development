# Team-RR1 Streamlit-based Recommender System
#### EXPLORE Data Science Academy Unsupervised Predict

## Overview

![Movie_Recommendations](resources/imgs/Image_header.png)

This repository houses all the essential resources and files for Team RR1's Recommender System Application Deployment focused on the Unsupervised Predict task Within EDSA's Data Science course

####  What is a Recommender System?

[![What is an API](resources/imgs/What_is_a_recommender_system.png)](https://youtu.be/Eeg1DEeWUjA)

Recommender systems play a crucial yet often overlooked role in today's technology-driven world. From search engines to online shopping, streaming platforms, and news feeds, these services heavily rely on recommendation algorithms to offer users the content they desire.

At its core, recommender systems work by finding similarities between people (users) and things (items). There are two main approaches: content-based and collaborative filtering. Content-based filtering matches items based on their attributes, while collaborative filtering identifies similarities among users to generate personalized recommendations.

During this Sprint, you will delve deeper into this concise explanation and explore the theoretical and practical aspects of recommendation algorithms. As you progress, you will gain a comprehensive understanding of how these algorithms drive personalized suggestions and enhance user experiences across various online platforms.    

####  Description of contents of this Repository

Below is a description of the contents within this repo:

| File Name                             | Description                                                       |
| :---------------------                | :--------------------                                             |
| `edsa_recommender.py`                 | Base Streamlit application definition.                            |
| `recommenders/collaborative_based.py` | collaborative filtering.                                          |
| `recommenders/content_based.py`       | Content-based filtering.                                          |
| `resources/data/`                     | Sample movie and rating data for app functionalities.             |
| `resources/models/`                   | Folder contains model and data binaries if produced.              |
| `utils/`                              | Folder for additional helper functions for the Streamlit app      |

## Solution Overview
This recommender system application leverages collaborative filtering and content-based filtering techniques to deliver personalized recommendations to users. Collaborative filtering analyzes user behavior to find similar users and suggest items they may like. Content-based filtering focuses on item attributes and matches them with user preferences. 

The graphical user interface is designed to give you option to choose either content based or collaborative base systems or the collaborative based systems. With these two approaches, our system provides accurate and diverse recommendations for enhanced user experience. Integrated into various platforms, our application continuously updates and refines suggestions in real-time. By understanding user preferences and item attributes, our application enhances engagement and user satisfaction.

NB: Now more than ever innovations are constantly needed to keep humanity in check for dynamism hence, we will continue to improve on the systems and bring to you more precision, accuracy and efficiency

## Conclusion:
With the collaborative and content-based recommender system, we aim to enhance user satisfaction, increase engagement, and drive user retention on various platforms. By understanding user preferences and item attributes, our application enables a more personalized and enjoyable user experience, making it a valuable addition to any data-driven platform.
