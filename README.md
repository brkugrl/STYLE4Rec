# Style4Rec: Enhancing Transformer-based E-commerce Recommendation Systems

This repository contains information about the paper titled **"Style4Rec: Enhancing Transformer-based E-commerce Recommendation Systems with Style and Shopping Cart Information."**
Style4Rec is a collaboration with AviviD.ai, it utilizes AviviD.ai's dataset. The main goal is to improve the sequential product recommendation performance by using style information that is extracted via product images, for E-commerce websites. Since the e-product images look very similar within the same product group, we developed a system that extracts the style information from the initial layers of an object detection model. 

## Abstract

Understanding users’ product preferences is essential to the efficacy of a recommendation system. Style4Rec is a transformer-based e-commerce recommendation system that integrates style and shopping cart information to improve sequential product recommendations. It outperforms state-of-the-art benchmarks, demonstrating significant improvements across various metrics such as HR@5, NDCG@5, and MRR@5.

## Key Contributions

1. **Novel Transformer-Based Model:** Developed a multi-layer transformer-based sequential recommendation system.
2. **Style Embeddings:** Incorporated neural style transfer to extract style information from product images, enhancing recommendation performance.
<p align="center">
      <img width="454" alt="image" src="https://github.com/user-attachments/assets/f156ce48-56ce-4ef5-a953-0407554cc0b3" />
</p>
<p align="center">
      <img width="458" alt="image" src="https://github.com/user-attachments/assets/d9d6d3f7-e641-4d73-9b7b-b5ffcd673280" />
</p>
<p align="center">
      Figure: Style loss Calculation
</p>
 


4. **Shopping Cart Data Utilization:** Differentiated between purchase and shopping cart sessions to reflect user interests more effectively.
5. **Performance Improvements:** Achieved notable gains over benchmarks like BERT4Rec and SASRec across multiple evaluation metrics.

## Methodology

- **Deep Transformer Encoder:** Utilizes multi-head self-attention mechanisms to capture dependencies in user sessions.
- **Style Embeddings:** Extracted using the neural style transfer algorithm, leveraging VGG-19 convolutional layers.
- **Shopping Cart Data:** Included shopping cart sessions during training and validation to reflect real-world user behavior.

## Results

The proposed model, Style4Rec, achieved the following improvements over benchmarks:

<img width="945" alt="image" src="https://github.com/user-attachments/assets/cbcb5ec9-9312-48f1-aae4-85408609b1c5" />
<img width="970" alt="image" src="https://github.com/user-attachments/assets/7cbd9bec-961b-48e7-bd98-9032267bcfe6" />

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
  Email: brkugrl96@gmail.com

---

This repository is dedicated to sharing insights from the research paper.  **No source code is provided here due to the NDA signed between AviviD.ai and the Interdisciplinary Data Science & Signal Processing Lab of National Taiwan University.**
