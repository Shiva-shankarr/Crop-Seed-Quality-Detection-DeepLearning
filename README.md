﻿# Seed Quality Detection System

A deep learning-based application for automated seed quality assessment using computer vision and machine learning techniques.

## 🌟 Features

- Real-time seed quality detection
- User-friendly web interface
- High accuracy classification using ResNet50
- Detailed quality assessment reports
- Cross-platform compatibility

## 🛠️ Tech Stack

### Backend
- Python 3.8+
- Flask
- TensorFlow/Keras
- NumPy
- Pillow (PIL)

### Frontend
- React.js
- JavaScript/ES6+
- CSS3
- HTML5

### Machine Learning
- TensorFlow 2.x
- ResNet50 Architecture
- Image Processing Libraries

## 📋 Prerequisites

- Python 3.8 or higher
- Node.js 14.x or higher
- npm or yarn
- Git

## 🚀 Installation

1. **Clone the repository**
```bash
git clone https://github.com/Shiva-shankarr/seedQualityDetection.git
cd seedQualityDetection
```

2. **Setup Backend**
```bash
# Windows
.\setup_dependencies.ps1

# Linux/Mac
chmod +x setup_dependencies.sh
./setup_dependencies.sh
```

3. **Setup Frontend**
```bash
cd frontend
npm install
```

## 💻 Running the Application

1. **Start Backend Server**
```bash
cd backend
python app.py
```
The backend server will start on http://localhost:5000

2. **Start Frontend Development Server**
```bash
cd frontend
npm start
```
The frontend will be available at http://localhost:3000

## 📁 Project Structure

```
seedQualityDetection/
├── backend/
│   ├── app.py              # Flask server
│   └── README.md
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── start.sh
├── model/
│   ├── train_model.py
│   └── seed_classifier_resnet50.h5
├── dataset/
├── evaluate/
├── test/
├── setup_dependencies.sh
├── setup_dependencies.ps1
└── setup.sh
```

## 🔧 Configuration

### Backend Configuration
- Model path: Update `MODEL_PATH` in `backend/app.py`
- Server port: Default is 5000 (configurable in app.py)
- Image size: Default is 224x224 pixels

### Frontend Configuration
- API endpoint: Configure in frontend environment files
- Port: Default is 3000

## 🎯 Usage

1. Access the web interface at http://localhost:3000
2. Upload a seed image using the interface
3. Click "Analyze" to process the image
4. View the detailed quality assessment results

## 🤖 Model Training

To train the model with your own dataset:

1. Prepare your dataset in the `dataset` directory
2. Configure training parameters in `model/train_model.py`
3. Run the training script:
```bash
python model/train_model.py
```

## 📊 Evaluation

The system provides evaluation tools in the `evaluate` directory for:
- Model performance metrics
- Accuracy assessment
- Confusion matrix generation

## 🧪 Testing

Run tests using:
```bash
cd test
python -m pytest
```

## 📈 Performance

- Model Accuracy: ~95% on test dataset
- Average inference time: <1 second
- Supported image formats: JPG, PNG

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- B.Shiva Shankar 

## 🙏 Acknowledgments

- ResNet50 architecture
- TensorFlow team
- Open source community

