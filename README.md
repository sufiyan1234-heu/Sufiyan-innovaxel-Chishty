# URL Shortener 🔗

A full-stack URL shortening service with analytics powered by Django REST Framework and Next.js.

## Features ✨
- 🚀 Instant URL shortening with custom slugs
- 📊 Click analytics with Recharts visualizations
- 🔄 Real-time updates with React Hot Toast notifications
- 📱 Responsive mobile-first design
- 📋 Copy to clipboard functionality
- 🛠️ URL management (Create, Read, Update, Delete)

## Tech Stack 🛠️

### Backend
- **Django REST Framework**
- Python 3.10+
- django-cors-headers

### Frontend
- **Next.js** 15.2.2
- **React** 19
- Tailwind CSS 3
- Axios 1.8.3
- React Hook Form 7.54.2
- Heroicons 2.2.0
- Recharts 2.15.1
- SweetAlert2 11.17.2

## Installation ⚙️

### Project Setup
Download the project code from the dev branch
you will get the backend and frontend folders

### Backend Setup

```bash
# navigate to project folder
cd backend 
cd urlshortner
```

```bash
# Create and activate virtual environment
python -m venv venv or python3 -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run development server
python manage.py runserver

```
### Fronten Setup
```bash
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

