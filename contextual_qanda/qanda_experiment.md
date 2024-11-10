# Question-Answering Experiment

## Objective
Evaluate NotebookLM's accuracy and relevance in answering specific questions.

## Document Used
- *Title*: Explainable Artificial Intelligence (XAI): What we know and what is left to attain Trustworthy Artificial Intelligence
- *Type*: Research Article   
- *Length*: 52
----------------
- *Title*: Explaining Image Captioning (Image to Text) using Azure Cognitive Services and Partition Explainer
- *Type*: Website
----------------
- *Title*: What is explainable AI?
- *Type*: Website

## Questions and Responses
**Question**: What are the trade-offs between accuracy and interpretability in explainable AI models

**Answer provided**: Accuracy vs. Interpretability Trade-off
The sources discuss the trade-off between accuracy and interpretability in explainable AI (XAI) models.
- Some experiments combine interpretable models to provide extra insight, but some interpretability may be sacrificed for a more accurate model.
- For example, Decision Trees (DT) are easy to interpret. But, combining multiple DTs into more complex models like Random Forests (RF) reduces interpretability.
- Complex models tend to be less interpretable but more accurate. Explainability aims to help us understand these complex systems.
- Figure 4 in source illustrates this balance between model performance (accuracy) and explainability (interpretability). Simpler models like DTs are easier to understand than RFs, which are easier to understand than Convolutional Neural Networks (CNNs).
- While a general trade-off between accuracy and interpretability is often assumed, some authors argue there’s no scientific evidence to support this claim.
- With careful design, a good interpretability-accuracy trade-off can be achieved. Sometimes, improving interpretability may also improve accuracy because it helps in understanding and refining the model.
- White-box models are interpretable by design, making their outputs easier to understand. However, they may be less accurate than black-box models.
- Gray-box models strive to achieve a balance between interpretability and accuracy.
- XAI aims to make AI systems more understandable and transparent without sacrificing performance.
- XAI techniques can be used to:
    - Build white/gray-box models that are interpretable by design while achieving high accuracy.
    - Provide black-box models with a minimum level of interpretability when white/gray-box models cannot reach an acceptable level of accuracy.
The sources also make a distinction between interpretability and explainability:
- Interpretability allows developers to understand the model's decision-making process, building confidence in the model's results. This is more for technically skilled users like developers.
- Explainability, on the other hand, provides insight into the model’s decision to the end-user to build trust in the AI system.
In conclusion, while a trade-off between accuracy and interpretability often exists, careful design can mitigate this trade-off. XAI techniques play a crucial role in balancing this trade-off, especially when using complex black-box models.


## Reference
Link to document: 
- https://www.ibm.com/topics/explainable-ai
- https://shap.readthedocs.io/en/latest/example_notebooks/image_examples/image_captioning/Image%20Captioning%20using%20Azure%20Cognitive%20Services.html
- https://www.sciencedirect.com/science/article/pii/S1566253523001148
