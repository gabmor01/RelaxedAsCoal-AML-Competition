# RelaxedAsCoal-AML-Competition
The competition asks to build robust translators / adapters that map text embeddings into the target vision latent space, so that mapped text embeddings match the ground-truth image embeddings produced by the provided VAE.
A pre-trained text encoder and a pre-trained VAE are provided with together with a training set of examples. Our model learns a mapping from the text-encoder space to the VAE latent space that generalises to the held-out test set.
