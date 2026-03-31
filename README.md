1. Impact of Data Augmentation
Data augmentation is a powerful "Generative" tool because it creates new training examples that the model has never seen before. It prevents overfitting—the model no longer just memorizes pixels; it learns the underlying shapes and features.

2. Challenges Encountered
The biggest challenge was managing Tensor shapes. Reshaping 2D images into 4D batches for the CNN required careful attention to detail. Additionally, ensuring file paths in Google Colab were correctly mapped (avoiding NameErrors) was a key learning moment.

3. Real-World Applications
These techniques are vital in fields with limited data. In Medical Imaging, we can augment a small set of X-rays to better train diagnostic AI. In Game Development (like Fortnite Creative), similar generative logic can be used to create endless variations of textures and landscapes based on a single "style" input.
