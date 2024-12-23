# Queryfy  

**Queryfy** is an AI-powered tool designed to automate the creation of structured questions from any text or PDF content. By leveraging advanced AI and seamless integrations, Queryfy transforms your input into quiz-ready questions in various formats.  

## Features  

- **Question Types Supported**:  
  - Multiple Choice Questions (MCQs)  
  - True/False  
  - Fill-in-the-Blank  
  - Subjective Questions  

- **Output Formats**:  
  - **PDF**: Download a well-structured question paper.  
  - **Google Form**: Generate and share questions directly as a Google Form.  

- **Technologies Used**:  
  - Google Generative AI for question generation.  
  - Google Forms and Drive APIs for seamless form creation and sharing.  

## Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/queryfy.git  
   cd queryfy  
   ```  

2. Install the required Python dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Set up your Google API credentials:  
   - Download your Google Service Account JSON file and place it in the project directory.  
   - Replace `your-jsonfilehere-437108-u7-9873e3487aaf.json` in the code with the actual file name.  

4. Add your Gemini API key to the environment variables:  
   ```bash  
   export GEMINI_API_KEY="your_api_key"  
   ```  

## Usage  

1. Run the application:  
   ```bash  
   python app.py  
   ```  

2. Open the web app in your browser:  
   - Navigate to `http://127.0.0.1:5000/`.  

3. Upload a PDF or enter text, select the question type, and choose the output format (PDF or Google Form).  

## Example Outputs  

- **PDF**:  
  A downloadable question paper with your selected question type.  

- **Google Form**:  
  A shareable Google Form link for quizzes, exams, or surveys.  

## License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

## Author  

**Vriddhi Jain**  
For contributions or inquiries, feel free to reach out via [GitHub](https://github.com/vriddhi23100).  
