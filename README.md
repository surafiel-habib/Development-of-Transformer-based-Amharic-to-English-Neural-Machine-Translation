# Transformer-Based Amharic-to-English Machine Translation with Character Embedding and Combined Regularization Techniques

Amharic, the official working language of the Federal Government of Ethiopia, is a Semitic language characterized by its morphological complexity and limited digital resources. These attributes pose significant challenges for natural language processing tasks, particularly machine translation.

This research introduces a Transformer-based Amharic-to-English neural machine translation model tailored to address these challenges. Key features of the model include:

- **Character-Level Embeddings: Captures Amharic’s intricate morphological structure and effectively handles out-of-vocabulary words.
- **Combined Regularization Techniques: Employs dropout with Elastic Net, L1, and L2 regularizations in the point-wise feed-forward network to enhance training stability and model generalization.

## Performance Highlights

The proposed model demonstrates substantial improvements over previous state-of-the-art methods for Amharic-to-English neural machine translation benchmarks:

- **BLEU Score: Achieved a BLEU score of 40.59, which is 7% higher than the prior state-of-the-art benchmark.
- **Best Regularization: The combination of L2 regularization with dropout applied to the point-wise feed-forward network achieved the best translation performance.
- **Parameter Efficiency: Reduced the model's parameters from 75 million to 5.4 million, significantly improving computational efficiency while maintaining high accuracy.

## Experimental Insights

The research addresses the unique challenges posed by low-resource and morphologically rich languages like Amharic. Extensive experiments showcase:

- Improvements in test accuracy and reduction in loss.
- Enhanced translation fidelity compared to models using word-level embeddings.
- Insights into leveraging character-level embeddings and combined regularization techniques to overcome challenges associated with low-resource languages.

### Future Directions

This research lays the groundwork for future studies, including:

- Exploring multilingual models to improve performance on low-resource languages.
- Optimizing attention mechanisms within Transformer architectures for better efficiency and accuracy.
- Broadening the application of hybrid regularization techniques in neural machine translation.

### Citation

If you use this research or code in your work, cite the corresponding paper: DOI: 10.1109/ACCESS.2024.3521985﻿

