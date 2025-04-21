🏥 Medical Image Analysis Platform
An advanced Streamlit-based medical image analysis application developed by Dhairya Goel, this platform allows users to upload and analyze medical images using AI models, generate explainable visualizations, collaborate via discussion chat, and perform report-based Q&A using OpenAI's GPT models.

🔍 Features
Upload and Analyze: Supports JPEG, PNG, DICOM, and NIfTI formats for medical image analysis.

Explainable AI: Visualize heatmaps and AI reasoning for better interpretability.

Medical References: Fetch relevant medical literature using PubMed integration.

Collaboration Tools: Discuss case findings with colleagues via a built-in chat interface.

Report Q&A System: Ask questions directly about AI-generated reports.

Comprehensive Reporting: Generate and download detailed PDF reports.

Statistics and History: Access historical analysis and generate statistical summaries.

## 🖼️ Screenshots

### 1. Upload Medical Images  
![Upload]![Screenshot 2025-04-21 140103](https://github.com/user-attachments/assets/dac22bce-7611-448c-a576-99ded9be4720)


### 2. Explainable AI - Heatmap Visualization  
![XAI Heatmap]![Screenshot 2025-04-21 140132](https://github.com/user-attachments/assets/67eaa41a-746f-44c7-8337-c1ae4a52fcf9)


### 3. AI-generated Report with Key Findings  
![Screenshot 2025-04-21 140414](https://github.com/user-attachments/assets/ac351cee-ca68-4942-9bce-fd477256fb60)


### 4. Interactive Q&A for Medical Reports  
![Q&A]![image](https://github.com/user-attachments/assets/8341baee-2a06-4aca-a32e-6e14ba7471a6)


---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python + OpenAI GPT APIs
- **Visualization**: Matplotlib, PIL
- **Medical Literature**: PubMed API
- **Image Formats**: JPEG, PNG, DICOM (.dcm), NIfTI (.nii, .nii.gz)

---

## 🔧 Installation

```bash
git clone https://github.com/DhairyaGoel05/AIDOCTOR.git
cd AIDOCTOR
pip install -r requirements.txt
streamlit run app.py

export OPENAI_API_KEY=your_api_key_here

📁 Project Structure
AIDOCTOR/
│
├── app.py                      # Main Streamlit app
├── utils_simple.py            # Image processing and analysis utils
├── chat_system.py             # Collaboration chat system
├── report_qa_chat.py          # Report QA backend
├── qa_interface.py            # Frontend for Q&A interface
├── screenshots/               # UI screenshots for README
│   ├── upload.png
│   ├── xai_heatmap.png
│   ├── report_generation.png
│   └── qa_interface.png
└── requirements.txt

📊 Sample Use Cases
Radiology report generation

Medical team collaboration

AI-driven second opinion

Research & literature support

🤝 Contributing
Contributions are welcome! Please open an issue or pull request.

