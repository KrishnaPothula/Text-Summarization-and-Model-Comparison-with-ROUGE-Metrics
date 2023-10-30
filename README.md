# Text-Summarization-and-Model-Comparison-with-ROUGE-Metrics
Automatically summarize text using BERTSUM, T5, and GPT-2 models, and compare their performance with ROUGE metrics.
If your Colab session is crashing during training, it's likely due to resource limitations. Training large models can be memory-intensive, and Colab's free GPU resources may not be sufficient for some tasks.
You may use, 
Local Machine or Server: If you have access to a more powerful machine or server with a dedicated GPU, consider running the training process locally. This will provide more resources and stability for training.
Colab Pro: Colab offers a paid version called Colab Pro that provides better GPU resources and more memory. Upgrading to Colab Pro may help with resource limitations.
Reduced Dataset: Train on a smaller subset of your data. If your dataset is large, reducing it can significantly reduce memory usage and training time. You can gradually increase the dataset size as needed.
Cloud Services: Consider using cloud-based GPU services like AWS, Google Cloud, or Microsoft Azure. These platforms offer GPU instances that can handle resource-intensive tasks like model training.
Distributed Training: Use multiple GPUs or distributed computing if available. This can be more efficient for large-scale training tasks.
Model Size: Choose a smaller model architecture. Smaller models require less memory and train faster.
Batch Size: Experiment with smaller batch sizes, which can reduce memory usage.
Checkpointing: Save model checkpoints at regular intervals so that you can resume training if it crashes.
Early Stopping: Implement early stopping so that you don't waste resources on training that isn't improving.
Optimize Code: Ensure that your code is optimized for memory usage. Avoid unnecessary data duplication and make sure you're releasing memory when it's no longer needed.
**
If you're experiencing crashes due to resource limitations in Colab, I recommend starting with a smaller dataset, reducing the model size, and experimenting with batch sizes to make the training process more manageable within the available resources.**
