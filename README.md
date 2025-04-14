# RevivePixels
Revive Pixels is a web-based tool that allows users to upload low-quality or blurry images and restore them using a simple deep learning model based on SRCNN (Super-Resolution Convolutional Neural Network). It enhances image clarity, making your old or low-res photos look sharper and cleaner — all in the browser!\

⚙️ How It Works

User Uploads an Image
Through a simple web interface, the user selects an image to enhance.

Image Processing via FastAPI Backend
The image is sent to a FastAPI backend where it's preprocessed and converted to a tensor.

Model Enhancement with SRCNN
A lightweight SRCNN model processes the image to enhance its resolution and sharpness.

Enhanced Image is Returned
The processed image is converted back to a viewable format and returned for download or preview.

🚀 Technologies Used
FastAPI – For creating the backend API
PyTorch – For the SRCNN deep learning model
Pillow (PIL) – For image processing
ngrok – To expose the local server on Colab to the internet
HTML + Form – For the upload UI
