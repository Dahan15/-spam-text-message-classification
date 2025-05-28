# Spam Text Message Classification

---

## 📄 Project Description  
This project focuses on classifying SMS messages as **spam** or **ham** (non-spam) using deep learning techniques.  
The dataset contains labeled SMS messages, and the goal is to build a model that automatically detects spam messages to improve message filtering.

---

## 🗂 Dataset  
The dataset contains two columns:  
- **Category**: Label for the message (spam or ham).  
- **Message**: The text content of the SMS message.  

The dataset has a total of 5572 messages.

---

## 🔧 Technologies and Tools Used  
- Python  
- Pandas  
- TensorFlow / Keras  
- Scikit-learn  

---

## ⚙️ Project Workflow

1. **Data Loading**: The dataset is loaded from a CSV file.  
2. **Label Encoding**: Convert categories (`spam`, `ham`) into numeric codes.  
3. **Text Tokenization**: Convert SMS text into sequences of integers using Keras Tokenizer.  
4. **Sequence Padding**: Pad sequences to ensure uniform input length for the model.  
5. **Train-Test Split**: Split data into training and testing sets.  
6. **Model Building**: A Sequential deep learning model with embedding, dense layers, and global average pooling.  
7. **Model Compilation**: Using binary cross-entropy loss and Adam optimizer.  
8. **Training**: Train the model to learn to classify spam messages.

---

## 🚀 How to Run  
1. Install required libraries if not installed:  
   ```bash
   pip install pandas tensorflow scikit-learn
2. Place the dataset CSV file (SPAM text message 20170820 - Data.csv) in your working directory.

3. Run the Python script or notebook with the code.

4. The model summary and training results will be displayed.

## 📈 Model Architecture Summary
1. Embedding layer with input vocabulary size of 1000 and embedding dimension of 128.

2. Dense layers with 'tanh' activation for learning complex patterns.

3. GlobalAveragePooling1D layer to reduce sequence dimension.

4. Output layer with sigmoid activation for binary classification.

## 👨‍💻 About the Developer
This project was developed by Abdulaziz M Dahan Ahmed.
Thank you for checking out this project!
