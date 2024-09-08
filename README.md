# k_shot-GAN-synthetic-data

Improving the generation of synthetic data in LLMs using k-shot prompting and a GAN.

Sentiment analysis is an important tool for businesses and governments that helps them better understand public opinions, allowing them to make decisions based on trends. A commonly used approach to sentiment analysis utilizes CNNs (Convolutional Neural Networks) which typically perform best when given large datasets. However, acquiring this data may be difficult to obtain and time-consuming. In order to address these problems, we present a new approach involving combining GANs and k-shot prompting for synthetic data generation using the Mistral-7B-v0.3 and Phi-3-Mini-4K models. 

# To start

1. Begin by running dataCleaning.ipynb.

2. Then run notebooks to train either GAN, k-shot, or k-shot + GAN. 

3. Next, generate a synthetic dataset using dataset generator.ipynb. 

4. Finally, to evaluate your models, run evals.ipynb

Requirements:
- Huggingface login credentials
