# Leaf-Diesease-Classification

**Project Overview: Leaf Disease Classification with TensorFlow and FastAPI**

**Introduction:**
In my project, I designed and implemented an advanced leaf disease classification system in three distinct stages using TensorFlow, FastAPI, and ReactJS. The primary goal was to develop a robust solution for identifying diseases in potato leaves, differentiating between a healthy leaf, early blight, and late blight. To achieve this, I employed machine learning techniques and modern web development practices.

**Project Components:**

1. **Machine Learning Model with TensorFlow:**
   - I utilized TensorFlow, a powerful open-source machine learning framework, to create a sophisticated classification model. This model was trained to distinguish between healthy potato leaves and leaves affected by early blight and late blight. TensorFlow's deep learning capabilities enabled the accurate classification of leaf diseases.

2. **FastAPI Backend:**
   - FastAPI, a high-performance web framework for building APIs with Python, was employed to develop the backend of the project. I created an API service that serves as the bridge between the machine learning model and the frontend interface. FastAPI ensured fast, efficient, and reliable communication between the frontend and the model.

3. **ReactJS Frontend:**
   - The user-friendly frontend was crafted using ReactJS, a popular JavaScript library for building dynamic user interfaces. The frontend allowed users to upload images of potato leaves directly from their devices. Through a seamless and intuitive interface, users could submit leaf images for disease classification.

**Project Workflow:**

1. **Leaf Image Upload:**
   - Users can upload images of potato leaves through the frontend interface. The intuitive design allows effortless image submission.

2. **Machine Learning Inference:**
   - Upon receiving the uploaded image, the FastAPI backend triggers the TensorFlow machine learning model. The model processes the image and performs a classification analysis.

3. **Disease Classification:**
   - The model accurately classifies the leaf into one of three categories: healthy leaf, early blight, or late blight. Each classification is accompanied by a confidence level, ensuring transparency and reliability in the results.

4. **User-Friendly Results:**
   - The results, along with the confidence level, are displayed on the frontend website. Users receive clear and understandable feedback about the condition of the submitted leaf.

**Technologies Used:**
- **Python:** The core programming language for implementing the machine learning model and backend API.
- **TensorFlow:** Leveraged for building and training the leaf disease classification model.
- **FastAPI:** Used to develop a high-performance backend API service for handling image uploads and model predictions.
- **ReactJS:** Employed for creating an interactive and responsive frontend interface, enabling users to upload leaf images and view results.

**Conclusion:**
In summary, my project showcases the seamless integration of machine learning, web development, and user experience design. By combining the power of TensorFlow, FastAPI, and ReactJS, I have created an innovative solution for potato leaf disease classification. This project not only demonstrates the potential of modern technologies but also provides a valuable tool for agricultural professionals and enthusiasts seeking accurate and efficient leaf disease diagnosis.
