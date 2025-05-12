# AI Health Assistant

## Description
The **AI Health Assistant** is an interactive web-based application designed to provide users with quick, AI-generated insights regarding health-related questions and symptoms. This application leverages the power of generative AI to offer useful and contextual information, such as disease-related data, precautions, medications, and recommended diets, based on user inputs. It acts as a conversational agent to assist users in understanding their symptoms and finding preliminary health-related answers.

### Key Features
- **Interactive Chat Interface**: Users can ask health-related questions and receive AI-generated responses.
- **Symptom-based Insights**: Provides detailed information on diseases, descriptions, precautions, medications, and diets related to user-inputted symptoms.
- **Dynamic Option Selection**: Offers selectable options for deeper insights on various aspects of the discussed symptoms.
- **Clear and Scrollable Chat History**: Maintains a record of user questions and AI responses in a visually appealing chat layout.
- **Responsive Design**: The interface adapts to different screen sizes, ensuring usability across devices.
- **Real-time AI Integration**: Integrates with a generative AI API for dynamic and context-aware responses.

## Tech Stack
- **Frontend**: React, HTML, CSS
- **Backend**: Axios for API calls
- **AI Integration**: Google Generative Language API (Gemini 1.5 Flash)
- **Deployment**: TBD

## How It Works
1. Users type a health-related question or symptom in the chat input field.
2. The application sends the input to the AI model via the Google Generative Language API.
3. AI-generated responses are displayed in the chat interface, along with options for further exploration (e.g., Disease, Description, Precaution, Medications, Diets).
4. Users can click on these options to delve deeper into specific aspects of the queried symptom.

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```bash
https://github.com/Brunda6/Virtual-Health-Hub/tree/main
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```bash
python app.py
```
- The app runs on **http://127.0.0.1:5000/**

## Usage
1. Open the application in your web browser.
2. Start asking health-related questions in the chat input box.
3. Interact with the chatbot and explore additional options provided for deeper insights.

## Screenshots
**Virtual Health Hub Homepage**

![image](https://github.com/user-attachments/assets/64570fa7-c03d-4b49-be41-a571363d1d69)


**Doctor Profiles with Chatbot Interaction**

![image](https://github.com/user-attachments/assets/3b139284-1880-4239-bdaa-d9926503a62a)


**AI Care - Symptom Analysis and Health Recommendations**

![image](https://github.com/user-attachments/assets/23c3a65a-c9a0-488e-8263-7609f5862d67)


**AI Health Assistant Interface**

![image](https://github.com/user-attachments/assets/af411b7c-1f04-459d-ab63-ae8e7847fb50)


## Future Enhancements
- **User Authentication**: Add login/signup features for personalized experiences.
- **Data Persistence**: Save chat history for future reference.
- **Improved AI Models**: Use advanced models for more accurate responses.
- **Multi-language Support**: Extend support for multiple languages to reach a wider audience.
- **Mobile App Version**: Develop a mobile application for on-the-go usage.

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or fixes.

---
**Note:** The AI Health Assistant is intended for informational purposes only and is not a substitute for professional medical advice, diagnosis, or treatment.
