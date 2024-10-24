# Brain Tumor Detection Using Deep Learning

This project focuses on detecting brain tumors from MRI images using a deep learning model built with PyTorch. The goal is to assist medical professionals by providing a tool that can classify MRI images as either containing a tumor or not.

##Overview:
    The project uses a Convolutional Neural Network (CNN) to analyze MRI images for tumor detection. It includes an end-to-end process from data loading and preprocessing to model training and evaluation.

##Features:
        Data Loading: Reads MRI image paths and labels from a CSV file.
        Data Preprocessing: Images are normalized, resized, and converted to grayscale.
        Model Building: A custom CNN architecture is implemented using PyTorch.
        Model Training: The model is trained using GPU acceleration (if available) for better performance.
        Prediction: Allows prediction on new MRI images to classify them as 'Tumor' or 'No Tumor'.
        
##Technologies Used:
        Programming Language: Python
        Libraries: PyTorch, torchvision, numpy, pandas, PIL
        Tools: Jupyter Notebook, Anaconda Navigator
        Planned Integration: Flask for deploying the model as a web application
