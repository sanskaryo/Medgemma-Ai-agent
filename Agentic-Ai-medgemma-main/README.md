# Agentic AI MedGemma

An intelligent medical AI assistant powered by Google's MedGemma model, designed to provide healthcare information and support through an agentic AI framework.

## 🚀 Features

- **Medical Question Answering**: Get accurate medical information powered by MedGemma
- **Agentic AI Framework**: Intelligent reasoning and decision-making capabilities
- **Interactive Frontend**: User-friendly interface for seamless interaction
- **RESTful API**: Backend services for integration and scalability

## 📋 Prerequisites

- Python 3.8+
- UV package manager (recommended) or pip

## 🛠️ Installation

### Using UV (Recommended)

1. **Install UV** (if not already installed):
   ```bash
   powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
   ```

2. **Clone the repository**:
   ```bash
   git clone https://github.com/sanskaryo/Agentic-Ai-medgemma
   cd Agentic-Ai-medgemma
   ```

3. **Set up virtual environment and install dependencies**:
   ```bash
   uv venv
   .venv\Scripts\activate  # Windows
   # source .venv/bin/activate  # Linux/Mac
   uv sync
   ```

### Using Pip (Alternative)

```bash
git clone https://github.com/sanskaryo/Agentic-Ai-medgemma
cd Agentic-Ai-medgemma
python -m venv venv
venv\Scripts\activate  # Windows
# source venv/bin/activate  # Linux/Mac
pip install -r requirements.txt
```

## 🚀 Usage

### Run the Application

```bash
# Start the main application
python main.py

# Or run the frontend separately
python frontend.py
```

### API Endpoints

The backend provides RESTful API endpoints for:
- Medical query processing
- AI agent interactions
- Health information retrieval

## 📁 Project Structure

```
Agentic-Ai-medgemma/
├── backend/              # Backend API services
├── frontend.py          # Frontend interface
├── main.py             # Main application entry point
├── pyproject.toml      # Project configuration
├── uv.lock            # UV dependency lock file
├── AI Therapist.pdf   # Documentation
└── README.md          # This file
```

## 🔧 Configuration

1. Set up your API keys and environment variables
2. Configure model parameters in the configuration files
3. Adjust frontend settings as needed

## 📚 Documentation

For detailed information about the AI Therapist functionality, refer to `AI Therapist.pdf`.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## ⚠️ Disclaimer

This AI assistant is for informational purposes only and should not replace professional medical advice. Always consult with qualified healthcare professionals for medical decisions.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Google's MedGemma model
- Open-source AI community
- Healthcare professionals who inspire better AI tools
- Ai with hassan

---

**Built with ❤️ for better healthcare accessibility**