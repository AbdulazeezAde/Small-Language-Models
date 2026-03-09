# Small Language Model (SLM) from Scratch: Indaba Nigeria 2026 Hands-on Session

## Overview

Welcome to Indaba Nigeria 2026! This hands-on session is your gateway to understanding and building a **Small Language Model (SLM)** from the ground up. In the spirit of `Indaba` (a traditional gathering for discussing important matters), we'll come together to demystify the magic behind language models. You'll not only learn the theoretical underpinnings but also get your hands dirty building a functional SLM with around 50-60 million parameters, capable of generating creative and coherent text.

This tutorial aims to make complex concepts accessible, providing a foundational understanding of how these powerful AI tools work, without requiring immense computational resources.

## What You'll Learn

By the end of this session, you will be able to:

*   **Prepare Data:** Load, explore, and tokenize a dataset (TinyStories) suitable for training a language model, and efficiently store tokenized data.
*   **Understand Model Architecture:** Deconstruct the core components of a Transformer-based language model, including token/positional embeddings, attention mechanisms, feed-forward networks, and weight tying.
*   **Configure & Setup Training:** Define model parameters (`GPTConfig`) and calculate parameter counts, as well as set up training hyperparameters, optimizers, learning rate schedulers, and mixed-precision training.
*   **Execute Model Training:** Understand and run a full training loop, including batch generation, forward/backward passes, loss calculation, gradient accumulation, and model checkpointing.
*   **Evaluate Performance:** Interpret training and validation loss plots to diagnose model behavior like overfitting or underfitting.
*   **Generate Text:** Use your trained SLM to generate new, creative text based on a given prompt, and decode the output into human-readable stories.

## Session Structure

This notebook is structured into several key steps:

*   **Step 1: Import and Explore the Dataset (TinyStories):** Get familiar with the data that will train our SLM.
*   **Step 2: Tokenize the Dataset:** Convert human language into a numerical format our model can understand.
*   **Step 3: Create Input-Output Batches:** Prepare the tokenized data for efficient training.
*   **Step 4: Define the SLM Model Architecture:** Build the core Transformer-based GPT model, including its configuration.
*   **Step 5: Define the Loss Function and Evaluation Metrics:** Set up how our model measures its learning progress.
*   **Step 6: Define SLM Training Configuration (Part 1: Hyperparameters):** Configure essential training parameters.
*   **Step 7: Define SLM Training Configuration (Part 2: Optimizer, Schedulers, Mixed Precision):** Implement advanced optimization techniques.
*   **Step 8: Pre-train the SLM:** Run the main training loop and watch the model learn.
*   **Step 9: Plot and Interpret the Loss Function:** Visualize and understand the model's learning curve.
*   **Step 10: Run SLM Inference and Generate Creative Stories:** Unleash your SLM's storytelling capabilities!

## Prerequisites

To get the most out of this session, a basic understanding of:

*   Python programming
*   Fundamental machine learning concepts
*   PyTorch (optional, but helpful)
*   Google Colab environment

is recommended. Don't worry if you're new to some of these; the tutorial is designed to guide you through each step.

## Let's Get Started!

Follow along with the cells, execute the code, and engage with the exercises. Don't hesitate to ask questions and experiment. We hope your SLMs will soon be writing better jokes than I can!
