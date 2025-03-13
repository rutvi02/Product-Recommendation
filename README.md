# Product-Recommendation

# Introduction to the problem
In today’s digital age, we are inundated with an overwhelming amount of information and choices. From online shopping platforms to streaming services, users often find it challenging to navigate the vast array of options available. Recommender systems have emerged as a critical tool to address this challenge, simplifying decision-making by suggesting relevant options tailored to individual interests and preferences.
Recommender systems play a vital role in enhancing user experiences and driving engagement. They enable the discoverability of new content, thereby enriching users' interactions with digital platforms. Additionally, in competitive markets, these systems boost user retention and contribute to company growth by delivering personalized experiences.
This report focuses on the performance comparison of an image-based fashion recommendation system utilizing three ResNet architectures: ResNet-18, ResNet-34, and ResNet-50. The system generates image descriptors by extracting feature embeddings from the penultimate layer of each ResNet variant. These embeddings are applied to a dataset of 44,000 fashion images and paired with the K-Nearest Neighbors (KNN) algorithm to recommend the five most visually similar products. The goal of this study is to evaluate how architectural depth impacts model complexity, preprocessing compatibility, and recommendation accuracy.
The rest of the report is structured as follows: first, a literature review discusses existing work in this area, providing a foundation for understanding the state-of-the-art approaches. The proposed work and its implementation are then detailed, followed by a description of the experiments investigating how data quality affects the results. The Results and Discussion section presents an analysis of the findings, and the Conclusion highlights key insights, limitations, and potential areas for future work. The report concludes with a division of tasks to outline the contributions of team members.


# Aproach 

<img width="679" alt="Screenshot 2025-03-13 at 7 13 35 PM" src="https://github.com/user-attachments/assets/51258638-d2c1-41cd-9189-59b58020d420" />
