# Development of Transformer-based Amharic to English Neural Machine Translation

Amharic, the official working language of the Federal Government of Ethiopia, is a Semitic language known for its morphological complexity and limited digital resources. These characteristics pose substantial challenges for natural language processing (NLP) tasks, particularly in machine translation (MT).

This project introduces a Transformer-based Amharic-to-English neural machine translation model designed to address these challenges. Key features of the model include:

- **Character-level Embeddings**: By using character-level embeddings, the model captures Amharic’s complex morphological structure and handles out-of-vocabulary (OOV) words more effectively.
- **Advanced Regularization Techniques**: The model integrates dropout, L1, L2, and Elastic Net regularizations to improve training stability and generalization.

## Performance Highlights

Our model demonstrates a substantial improvement over the previous state-of-the-art in Amharic-to-English neural machine translation benchmarks:

- **BLEU Score**: Achieved a BLEU score of 40.59, marking a 7% improvement over the prior benchmark.
- **Best Regularization**: The combination of L2 regularization with dropout applied to the point-wise feed-forward network yielded the highest translation performance.
- **Parameter Efficiency**: Reduced model parameters from 75 million to 5.4 million, achieving significant computational efficiency while maintaining high accuracy.

## Experimental Insights

The proposed approach provides insights into addressing the unique challenges of low-resource, morphologically rich languages like Amharic. Extensive experiments demonstrate improvements in test accuracy, reduction in loss, and enhanced translation fidelity over word-level embedding models.

### Future Directions

This research opens new avenues for future work, including:

- Exploring multilingual models for low-resource languages.
- Optimizing the attention mechanism within the Transformer architecture.
- Applying hybrid regularization techniques to further enhance model performance.