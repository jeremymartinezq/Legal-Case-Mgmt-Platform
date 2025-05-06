# LexIntelAI - AI-Optimized Legal Case Management System

An AI-powered Legal Case Management System that streamlines the entire legal case lifecycle, from intake to close, with advanced AI and ML capabilities.

![Screenshot 2025-05-06 020610](https://github.com/user-attachments/assets/f89efa6f-45bd-430b-a2c8-ca481877cdcb)
![Screenshot 2025-05-06 022600](https://github.com/user-attachments/assets/49739c9c-78ab-410a-9aad-ad5f0fa62a9f)
![Screenshot 2025-05-06 015246](https://github.com/user-attachments/assets/25537fa2-5d98-4dc0-8930-84544af39d70)
![Screenshot 2025-05-06 015336](https://github.com/user-attachments/assets/375097f5-ac6b-42e9-935f-633a48fe091d)
![Screenshot 2025-05-06 015607](https://github.com/user-attachments/assets/cd832f92-656c-439d-a718-cc0ba94a4881)
![Screenshot 2025-05-06 015625](https://github.com/user-attachments/assets/bdddd4aa-9be2-40c2-8925-e8c8639b3237)
![Screenshot 2025-05-06 015719](https://github.com/user-attachments/assets/7e7373f3-114b-45f1-872d-2842ecb30b64)
![Screenshot 2025-05-06 015759](https://github.com/user-attachments/assets/26503c34-61ee-4321-ab6e-fdfceaff2161)
![Screenshot 2025-05-06 015944](https://github.com/user-attachments/assets/d1c09bde-4d5d-4590-9035-59f2ef916331)
![Screenshot 2025-05-06 020547](https://github.com/user-attachments/assets/bb4cc51a-90a4-4d52-8c64-7e7421cb92bd)
![Screenshot 2025-05-06 020042](https://github.com/user-attachments/assets/791cb4a8-1621-47d3-83cc-369c3bd079a5)
![Screenshot 2025-05-06 020103](https://github.com/user-attachments/assets/3c4b47f4-d8dc-46f9-8d66-1aa79b9d0972)
![Screenshot 2025-05-06 020208](https://github.com/user-attachments/assets/912ca454-4dc6-425c-a0df-b91c003a9a3e)
![Screenshot 2025-05-06 020226](https://github.com/user-attachments/assets/c6e3ff57-6afa-4c54-a12c-486475ed2cd6)
![Screenshot 2025-05-06 020257](https://github.com/user-attachments/assets/a9c9bf88-fc40-450f-9cfd-0129989f747c)
![Screenshot 2025-05-06 020511](https://github.com/user-attachments/assets/96cfe267-dff2-4493-8f16-8a3e6ecc2a46)
![Screenshot 2025-05-06 020523](https://github.com/user-attachments/assets/a9689fa4-d884-47d3-8383-8a2c46689fee)
![Screenshot 2025-05-06 021126](https://github.com/user-attachments/assets/8bb3d1ee-7b0c-4729-96fe-309b63bb3076)
![Screenshot 2025-05-06 021142](https://github.com/user-attachments/assets/207d3556-e283-43f7-9760-284c8d3da386)
![Screenshot 2025-05-06 021156](https://github.com/user-attachments/assets/20a7e509-5e8e-4bb4-afb0-6ef69a139968)
![Screenshot 2025-05-06 014436](https://github.com/user-attachments/assets/2c7e188b-32f5-4de9-9e10-8a2630b8f5bd)


## Features

- **Case Management**: Complete case lifecycle tracking (intake → review → court → close)
- **AI Contract Review**: LegalBERT-powered contract analysis for risk assessment and summaries
- **Document Processing**: OCR with Tesseract and OpenCV for document digitization
- **Legal Chatbot**: Intelligent assistant for bookings and legal Q&A
- **Predictive Analytics**: ML models for case outcome prediction and billing anomaly detection
- **Role-based Access**: Tailored interfaces for Clients, Attorneys, and Administrators

## Tech Stack

### Backend
- FastAPI (Python)
- PostgreSQL
- Redis

### Frontend
- Next.js
- TailwindCSS
- TypeScript

### AI/ML Components
- LegalBERT for NLP
- Tesseract + OpenCV for OCR
- LangChain or Rasa for chatbot
- PyTorch, Scikit-learn for ML models

### Deployment
- Docker
- Kubernetes
- Terraform on AWS

## Project Structure

```
lexintelai/
│
├── backend/         # FastAPI backend
├── frontend/        # Next.js frontend
├── models/          # AI model files
├── data/            # Data storage
├── infra/           # Infrastructure as code
├── notebooks/       # Jupyter notebooks for ML
└── tests/           # Test files
```

## Getting Started

### Prerequisites
- Python 3.11+
- Node.js 16+
- Docker
- PostgreSQL
- Redis

### Installation
1. Clone the repository
2. Set up the backend:
   ```
   cd backend
   pip install -r requirements.txt
   uvicorn app.main:app --reload
   ```
3. Set up the frontend:
   ```
   cd frontend
   npm install
   npm run dev
   ```

## License
[MIT License](LICENSE) 

## Author
Developed by Jeremy Martinez-Quinones.
