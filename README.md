## Recommender System using the CLIP Model

A similarity based Recommender System was made using OpenAI's multimodal CLIP model
Tags are created using the features of the product. 
Embeddings of Textual tags are created using the CLIP model and embeddings of corresponding images from the same CLIP model were generated.
Both the embeddings were trained for similarity loss in the dataset.
Top five similar products are fetched.


Following is the link to dataset:
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

Following is the link to CLIP model in HuggingFace:
https://huggingface.co/openai/clip-vit-base-patch32
