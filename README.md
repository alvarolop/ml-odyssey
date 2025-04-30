# ML Odyssey

A personal exploration of machine learning concepts with Python, focused on practical examples from several sources.

## Purpose

The main goal of this repository is to learn and explore machine learning and deep learning step by step.

In addition, I aim to provide clear, easy-to-follow examples that anyone can deploy and test on their own infrastructure.

By sharing practical, reproducible code and workflows, I hope to make advanced machine learning concepts accessible to a wider audience and encourage hands-on experimentation.

## What You’ll Find Here

- **Jupyter Notebooks**:  
  Interactive notebooks for each major topic, featuring code, visualizations, and explanations. Notebooks are organized for clarity, reproducibility, and collaboration, leveraging the latest JupyterLab features, interactive widgets, and AI-powered code assistance.

- **Kubeflow Pipelines**:  
  For selected topics, Kubeflow pipeline implementations demonstrate scalable, production-oriented machine learning workflows. These pipelines are built using the latest Kubeflow Pipelines v2 SDK, supporting modularity, versioning, and enhanced visualization.

- **[WIP] Modern ML Tools**:  
  Integration of tools such as AutoML, Hugging Face models, Dask for parallel computing, and GPU acceleration for deep learning tasks.

## How to start with predictive AI?

If you want to start with predictive AI and don't have any guidance or external references, you might find that there are plenty of resources, tools, and frameworks but that it is difficult to know which ones to use or even what they are used for. In this section, I'll try to provide a concise definition so that you can get a glimpse of when to choose each of them.

### TensorFlow and Keras

TensorFlow is an end-to-end open-source platform for machine learning, and Keras is its high-level API for building and training deep learning models.

- 🌟 **Ease of Use**: Keras simplifies model building with an intuitive API, making it beginner-friendly.
- 🚀 **Scalability**: TensorFlow supports distributed training and deployment on various platforms, including mobile and edge devices.
- 📊 **Visualization**: Integrated with TensorBoard for monitoring metrics, debugging, and visualizing model performance.
- 🌐 **Wide Adoption**: Backed by Google, TensorFlow has extensive community support, a rich ecosystem of pre-trained models, and compatibility with tools like TensorFlow Lite and TensorFlow.js.

**When to Use TensorFlow?**  
TensorFlow is ideal for production-grade machine learning workflows, large-scale deployments, and scenarios requiring cross-platform compatibility (e.g., mobile or web). Its integration with Keras makes it accessible for beginners while still offering advanced features for experts.

**Relationship**: Keras was originally developed as an independent library but is now tightly integrated into TensorFlow as its official high-level API. This integration allows seamless access to TensorFlow's advanced features while maintaining Keras's simplicity.

---

### PyTorch

PyTorch is an open-source machine learning framework that provides a flexible and dynamic computation graph for deep learning.

- 🧩 **Dynamic Graphs**: Enables real-time debugging and flexibility in model building, making it easier to experiment with new ideas.
- 🖥️ **GPU Acceleration**: Optimized for CUDA, PyTorch excels in leveraging GPUs for fast computation, making it a favorite for research.
- 🛠️ **Rich Ecosystem**: Includes domain-specific libraries like TorchVision (computer vision), TorchText (NLP), and TorchAudio (speech processing).
- 🧪 **Research-Oriented**: PyTorch's Pythonic design and flexibility make it the preferred choice for academic research and prototyping.

**When to Use PyTorch?**  
PyTorch is best suited for research, experimentation, and scenarios where flexibility and debugging are critical. Its dynamic computation graph allows for quick iteration, making it ideal for developing novel architectures or testing new ideas.

**Can Keras be used in the PyTorch context?**  
No, Keras is specifically designed to work with TensorFlow and does not natively support PyTorch. However, PyTorch has its own high-level APIs, such as `torch.nn` and libraries like `PyTorch Lightning`, which provide similar functionality to Keras for simplifying model development and training.

---

### Scikit-learn

Scikit-learn is a simple and efficient library for data mining and machine learning in Python.

- 📈 **Classic ML**: Focused on traditional machine learning algorithms like regression, classification, and clustering.
- 🛠️ **Preprocessing Tools**: Includes utilities for data transformation and feature selection.
- 🧪 **Integration**: Works seamlessly with NumPy, SciPy, and pandas.
- 🖥️ **Lightweight**: Ideal for small to medium-sized datasets and quick prototyping.

---

### What They Are Not Used For

While TensorFlow, PyTorch, and Scikit-learn are powerful tools, there are specific areas in machine learning where other tools are better suited:

- **TensorFlow and PyTorch**:  
  - ❌ Not ideal for **traditional machine learning algorithms** like regression, decision trees, or clustering.  
    Use **Scikit-learn** or **XGBoost** for these tasks.
  - ❌ Not the best choice for **automated machine learning (AutoML)** workflows.  
    Use tools like **H2O.ai**, **Google AutoML**, or **DataRobot** instead.

- **Scikit-learn**:  
  - ❌ Not designed for **deep learning** or tasks requiring GPU acceleration.  
    Use **TensorFlow**, **PyTorch**, or **JAX** for these scenarios.
  - ❌ Limited for **large-scale distributed training** or production-grade pipelines.  
    Use **TensorFlow Extended (TFX)**, **Kubeflow**, or **Ray** for scalable workflows.

## Repository usage

Now that we have a better idea of the purpose of each library, we will explore how to use them effectively in practical scenarios. Each section of the repository is designed to guide you through hands-on examples, starting from basic concepts and progressing to advanced workflows.

## Credits

This repository draws inspiration from mainly two books:

- `Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition by Aurélien Géron (O’Reilly, 2019)`.
- `Deep Learning with PyTorch, 1st Edition by Eli Stevens, Luca Antiga, and Thomas Viehmann (Manning, 2020)`.

While the code and examples here are original and make use of different datasets, I would like to acknowledge those books for their accessible approach to complex machine learning topics.

This project also reflects the knowledge and skills developed during my studies in the `Máster in Business Analytics & Big Data` at IMF Smart Education, in collaboration with Indra.

Let me know if you’d like further refinements or additions!

