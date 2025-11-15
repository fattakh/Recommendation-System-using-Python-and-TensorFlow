Recommendation System using Python & TensorFlow

This project demonstrates how to build a content-based recommendation system using Python, TensorFlow, and a real Netflix 2023 dataset.
The model learns similarities between titles using metadata such as content type, language, and viewing hours—without requiring any user behavior data.

📌 Features

📑 Preprocessing of Netflix metadata

🔢 Encoding of categorical fields for deep learning

🧠 TensorFlow embedding model to learn content similarity

🎯 Self-supervised training strategy

🎧 Function to recommend similar shows/movies (e.g., “If you liked Wednesday…”)

🛠️ Tech Stack

Python

TensorFlow / Keras

Pandas

NumPy

📂 Dataset

This project uses a Netflix 2023 content metadata dataset containing:

Title

Language

Content Type

Hours Viewed

Availability

Release Date

(Add your dataset link here if available.)

🚀 How It Works

Load & explore the dataset

Clean & preprocess data (encode categories, handle duplicates, format numbers)

Build a neural recommendation model with embeddings

Train using self-supervised learning

Generate recommendations using similarity in embedding space
