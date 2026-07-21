# Fundamentals of Deep Learning — Notes

PyTorch notebooks written while reading *Fundamentals of Deep Learning* (O'Reilly). Each one is a hands-on implementation of a concept from the book, not a copy of the book's code.

## Notebooks

- **CNN_mini_project.ipynb** — CNN image classifier on CIFAR-10 using `torchvision`. Custom `Net` module built from two `nn.Sequential` conv blocks, trained with a `DataLoader`/`random_split` pipeline.
- **Sentiment_Analysis_Using_LSTM.ipynb** — Sentiment classifier on the IMDB dataset (via Hugging Face `datasets`). Hand-rolled tokenizer/encoder, custom `IMDBDataset`, and an `Embedding -> LSTM -> Linear` classifier (`TextClassifier`).
- **VAE.ipynb** — Variational Autoencoder on MNIST. Gaussian MLP encoder / Bernoulli MLP decoder, reparameterization trick, custom VAE loss, with reconstructions saved to `VAE_reconstruction.png`.

## Key Takeaways 

Learning about neural networks in summer 2026 was cool, I enjoyed learning about the history of advancement in this field from CNN to LSTM to transformers. I also found Reinforcement Learning an interesting field to look up in the future.