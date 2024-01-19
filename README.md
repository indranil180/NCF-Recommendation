# NCF-Recommendation

Although numerous recommender system architectures exist, I was particularly drawn to the research presented in "NCF: Neural Collaborative Filtering" (https://arxiv.org/pdf/1708.05031.pdf). This paper proposes a novel neural architecture that eschews the traditional inner product on user and item latent features for a more sophisticated approach.
Inspired by James Loy's work, I recreated this notebook on Kaggle.

In this notebook i used implicit feedback to develop the recommender system using pytorch lightning.
To evaluate the performance of item recommendation,leave-one-out evaluation is adopted, which has been widely used in recommender system world.
The MovieLens dataset is a natural choice for this exercise, mirroring the data used in the paper's own architecture evaluation.
