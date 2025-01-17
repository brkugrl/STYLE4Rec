# Style4Rec: Enhancing Transformer-based E-commerce Recommendation Systems

This repository contains information about the paper titled **"Style4Rec: Enhancing Transformer-based E-commerce Recommendation Systems with Style and Shopping Cart Information."**

## Abstract

Understanding users’ product preferences is essential to the efficacy of a recommendation system. Style4Rec is a transformer-based e-commerce recommendation system that integrates style and shopping cart information to improve sequential product recommendations. It outperforms state-of-the-art benchmarks, demonstrating significant improvements across various metrics such as HR@5, NDCG@5, and MRR@5.

## Key Contributions

1. **Novel Transformer-Based Model:** Developed a multi-layer transformer-based sequential recommendation system.
2. **Style Embeddings:** Incorporated neural style transfer to extract style information from product images, enhancing recommendation performance.
3. **Shopping Cart Data Utilization:** Differentiated between purchase and shopping cart sessions to reflect user interests more effectively.
4. **Performance Improvements:** Achieved notable gains over benchmarks like BERT4Rec and SASRec across multiple evaluation metrics.

## Methodology

- **Deep Transformer Encoder:** Utilizes multi-head self-attention mechanisms to capture dependencies in user sessions.
- **Style Embeddings:** Extracted using the neural style transfer algorithm, leveraging VGG-19 convolutional layers.
- **Shopping Cart Data:** Included shopping cart sessions during training and validation to reflect real-world user behavior.

## Results

The proposed model, Style4Rec, achieved the following improvements over benchmarks:

| Metric      | BERT4Rec | SASRec | Style4Rec |
|-------------|-----------|--------|-----------|
| **HR@5**    | 0.677     | 0.681  | **0.735** |
| **NDCG@5**  | 0.583     | 0.594  | **0.674** |
| **MRR@5**   | 0.552     | 0.559  | **0.654** |

These results demonstrate the effectiveness of incorporating style information and shopping cart data in transformer-based recommendation systems.

## Dataset

The model was evaluated using an e-commerce dataset provided by a partnering company. It included:
- User purchase data.
- Shopping cart data.
- Product images.

## Citation

If you find this work useful, please cite:

```
@article{ugurlu2025style4rec,
  title={Style4Rec: Enhancing Transformer-based E-commerce Recommendation Systems with Style and Shopping Cart Information},
  author={Berke Ugurlu, Ming-Yi Hong, Che Lin},
  journal={arXiv preprint arXiv:2501.09354},
  year={2025}
}
```

## Contact

For any questions or collaborations, please contact:
- **Berke Ugurlu**  
  Email: berke.ugurlu@example.com

---

This repository is dedicated to sharing insights from the research paper. No source code is provided here.
