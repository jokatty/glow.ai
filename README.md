# Glow.ai - AI-Powered Beauty & Aesthetic Enhancement

<div align="center">
  <img src="assets/logo.png" alt="Glow.ai Logo" width="200"/>
  <p><em>Transform your selves with AI</em></p>
</div>

## 🌟 Overview

Glow.ai is an innovative AI-powered application that revolutionizes beauty and aesthetic enhancement through advanced machine learning algorithms. Our platform offers personalized beauty recommendations, virtual try-ons, skin analysis, and aesthetic consultations powered by state-of-the-art AI technology.

## What problem does the app solve:

Users concerned with their aesthetics can get a glimps of their future selves post treatment.

## ✨ Features

### 🎨 Virtual Beauty Try-On

- **Real-time AR filters** for makeup, hairstyles, and accessories
- **Skin tone matching** for accurate color recommendations
- **Before/after comparisons** with realistic transformations
- **Multiple style presets** for different occasions

### 🔬 AI-Powered Skin Analysis

- **Comprehensive skin assessment** using computer vision
- **Personalized skincare recommendations** based on skin type and concerns
- **Progress tracking** with detailed analytics
- **Ingredient analysis** for product compatibility

### 💄 Personalized Beauty Recommendations

- **AI-driven product suggestions** based on your unique features
- **Trend analysis** and style recommendations
- **Seasonal adjustments** for optimal beauty routines

### 📱 Smart Beauty Assistant

- **Voice-activated beauty consultations**
- **Step-by-step tutorial generation**
- **Beauty routine optimization**
- **Appointment scheduling** with beauty professionals

## 🛠️ Technology Stack

### Frontend

- **Next.js 14** - Full-stack React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Framer Motion** - Smooth animations
- **Shadcn/ui** - Beautiful, accessible components
- **React Native** - Cross-platform mobile support

### Backend

- **FastAPI** - High-performance Python API framework
- **Python 3.11+** - AI/ML processing and data science
- **Pydantic** - Data validation and serialization
- **Uvicorn** - ASGI server for production
- **Celery** - Background task processing for AI operations

### AI/ML

- **TensorFlow** - Deep learning framework
- **OpenCV** - Computer vision processing
- **MediaPipe** - Face detection and tracking
- **Stable Diffusion** - Image generation
- **Hugging Face** - Pre-trained models

### Database & Storage

- **PostgreSQL** - Primary database
- **Redis** - Caching and sessions
- **AWS S3** - Image and media storage
- **MongoDB** - User preferences and analytics

### Infrastructure

- **Docker** - Containerization
- **GCP** - Cloud infrastructure
- **CI/CD** - GitHub Actions

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- Python (v3.9 or higher)
- Docker and Docker Compose
- Git

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/glow.ai.git
   cd glow.ai
   ```

2. **Install dependencies**

   ```bash
   # Frontend dependencies
   cd frontend
   npm install

   # Backend dependencies
   cd ../backend
   npm install

   # Python dependencies
   cd ../ai-services
   pip install -r requirements.txt
   ```

3. **Start the development environment**

   ```bash
   docker-compose up -d
   ```

4. **Access the application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:8000
   - AI Services: http://localhost:5000

## 📱 Mobile App

Our mobile application is available on:

- **iOS App Store**:
  @TODO

## 🔧 Configuration

### Environment Variables

```env
# Database
DATABASE_URL=postgresql://user:password@localhost:5432/glow_ai
REDIS_URL=redis://localhost:6379

# GCP Configurations

# AI Services
OPENAI_API_KEY=your_openai_key
HUGGINGFACE_API_KEY=your_huggingface_key

# Authentication
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
```

## 📊 API Documentation

Our API documentation is available at:

- **Swagger UI**: http://localhost:8000/docs

### Key Endpoints

- `POST /api/v1/analyze-skin` - Skin analysis
- `POST /api/v1/virtual-tryon` - Virtual beauty try-on
- `GET /api/v1/recommendations` - Beauty recommendations
- `POST /api/v1/consultation` - AI beauty consultation

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
