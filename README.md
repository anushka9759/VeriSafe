# VeriSafe
# VeriSafe&#x20;

### See Beyond the Screen. Trust What You See.

**VeriSafe** is a web application designed to support digital trust through deepfake detection, media verification, and cybersecurity awareness. It aims to help users examine digital content, identify potential signs of manipulation, and make more informed decisions about what they see online.

In a world where digital content can be manipulated, VeriSafe aims to make verification more accessible and understandable.

---

## 🚀 Key Features

- **Media Scan:** Examine supported images and videos for potential signs of manipulation.
- **Cyber Scan:** A dedicated area for cybersecurity-related scanning and checks, depending on the implemented functionality.
- **Trust Checks:** Support additional media authenticity and verification checks.
- **Scan History:** Access previous scan records, where supported by the application.
- **User-Friendly Interface:** A straightforward interface designed to make digital verification easier to navigate.

*Detection results are indicators, not absolute proof that media is authentic or manipulated.*

## 🎯 Our Mission

To make digital trust more accessible by helping people approach online media with greater awareness, caution, and confidence.

## 🛠️ Technology Stack

**Frontend**

- React
- TypeScript
- Vite
- CSS

**Backend**

- Python
- FastAPI
- SQLite

**Additional Technologies**

- REST API integration
- SHA-256 hashing and media authenticity checks, where implemented

## Project Structure

```text
VeriSafe/
├── frontend/
│   ├── public/
│   ├── src/
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   └── vite.config.js
│
├── backend/
│   ├── main.py
│   └── other backend modules
│
└── README.md
```

*The structure above is illustrative. Actual folders and files may differ in your repository.*

## ⚙️ Getting Started

### Prerequisites

Install the following before running the project:

- Node.js and npm
- Python 3
- Git

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd VeriSafe
```

Replace the placeholder with your repository's HTTPS URL.

### 2. Run the Frontend

Open a terminal in the frontend directory:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed by Vite in your browser, commonly `http://localhost:5173`.

### 3. Run the Backend

Open a separate terminal in the backend directory:

```bash
cd backend
python -m venv .venv
```

Activate the virtual environment.

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

Install the project's dependencies using its existing `requirements.txt`, if provided:

```bash
pip install -r requirements.txt
```

Start the FastAPI application if its entry point is `main.py` and the application instance is named `app`:

```bash
uvicorn main:app --reload
```

The API documentation is commonly available at `http://127.0.0.1:8000/docs`.

**Note:** These commands assume the backend has a `requirements.txt` file and uses the stated entry point. Follow the project's actual configuration if it differs. Configure the frontend's API base URL to match the running backend.

## Security and Privacy

- Never commit API keys, passwords, access tokens, or private environment files.
- Keep `.env` files out of version control.
- Do not upload `node_modules`, virtual environments, or generated build directories.
- Handle uploaded media and scan results responsibly.



## &#x20;Future Scope

Potential improvements include:

- Enhanced image and video analysis.
- More comprehensive media authenticity verification.
- Improved cybersecurity checks.
- Clearer explanations of scan results.
- Better privacy controls and deployment support.

These are possible future enhancements, not claims about currently implemented features.

##

## 📄 License

A license has not yet been specified. Add a license file if you intend to publish the project under an open-source license.

---

**VeriSafe — Because trust deserves verification.**
