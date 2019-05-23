# kaggle-jigsaw-unintended-bias-in-toxicity-classification

https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/overview

```
Here’s the background: When the Conversation AI team first built toxicity models, they found that the models incorrectly learned to associate the names of frequently attacked identities with toxicity. Models predicted a high likelihood of toxicity for comments containing those identities (e.g. "gay"), even when those comments were not actually toxic (such as "I am a gay woman"). This happens because training data was pulled from available sources where unfortunately, certain identities are overwhelmingly referred to in offensive ways. Training a model from data with these imbalances risks simply mirroring those biases back to users.
```

## runbook

1. Runs in a GCP AI Platform Tensorflow:2.0 environment.
2. Expects Kaggle integration to be configured (for example with a `~/.kaggle`).
