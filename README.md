# AI Health Assistant 🏥

A professional AI-powered health assistant chatbot that can analyze medical reports, predict potential diseases, and provide health advice using the Anthropic Claude API.

## Features ✨

- **Interactive Chat Interface**: Clean, modern, and responsive design
- **Image Upload**: Upload medical reports, lab results, X-rays, and other health-related images
- **PDF Support**: Upload and analyze PDF medical documents
- **Health Analysis**: Get insights about potential health concerns from your reports
- **Disease Prediction**: AI-powered analysis to identify possible health risks
- **Natural Conversations**: Ask health-related questions in plain language
- **Professional UI**: Beautiful gradient design with smooth animations

## Prerequisites 📋

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- An Anthropic API key (get one at https://console.anthropic.com/)
- Basic web hosting (optional - can run locally)

## Setup Instructions 🚀

### Step 1: Get Your API Key

1. Go to [Anthropic Console](https://console.anthropic.com/)
2. Sign up or log in to your account
3. Navigate to API Keys section
4. Create a new API key and copy it

### Step 2: Configure the Application

1. Open the `script.js` file in a text editor
2. Find this line near the top:
   ```javascript
   const API_KEY = 'YOUR_API_KEY_HERE';
   ```
3. Replace `'YOUR_API_KEY_HERE'` with your actual API key:
   ```javascript
   const API_KEY = 'sk-ant-api03-...-your-actual-key-here';
   ```
4. Save the file

### Step 3: Run the Application

**Option A: Run Locally**
1. Place all files (`index.html`, `styles.css`, `script.js`) in the same folder
2. Open `index.html` in your web browser
3. Start chatting with your AI Health Assistant!

**Option B: Deploy to Web Server**
1. Upload all files to your web hosting service
2. Ensure all files are in the same directory
3. Access the application through your domain

## File Structure 📁

```
your-project-folder/
│
├── index.html          # Main HTML file
├── styles.css          # Styling and design
└── script.js           # JavaScript logic and API integration
```

## How to Use 💡

### Basic Chat
1. Type your health-related question in the input box
2. Press Enter or click the send button
3. Wait for the AI to analyze and respond

### Upload Medical Reports (Images)
1. Click the paperclip (📎) icon
2. Select an image file (JPG, PNG, etc.) of your medical report
3. The image will appear in the preview area
4. Type your question about the report or just ask "Please analyze this report"
5. Send the message

### Upload Medical Reports (PDF)
1. Click the paperclip (📎) icon
2. Select a PDF file containing your medical report
3. The PDF name will appear in the preview area
4. Add your question or instructions
5. Send the message

### Example Questions

**General Health:**
- "What are the symptoms of diabetes?"
- "How can I improve my heart health?"
- "What should I know about high blood pressure?"

**Report Analysis:**
- Upload a blood test report and ask: "Can you analyze this blood test? Are there any concerns?"
- Upload an X-ray and ask: "What do you see in this X-ray?"
- Upload a full health checkup report and ask: "Based on these results, what diseases should I watch out for?"

**Preventive Care:**
- "What health screenings should I get at age 35?"
- "How can I prevent cardiovascular disease?"
- "What are early warning signs of kidney problems?"

## Important Disclaimer ⚠️

This AI Health Assistant is designed to provide information and insights, but it is **NOT a replacement for professional medical advice, diagnosis, or treatment**. 

- Always consult with qualified healthcare professionals for medical decisions
- In case of emergency, contact emergency services immediately
- Do not delay seeking medical care based on AI advice
- The AI's analysis is based on the information provided and may not be complete

## API Costs 💰

This application uses the Anthropic Claude API, which is a paid service:
- You will be charged based on your API usage
- Costs are calculated per 1000 tokens (roughly 750 words)
- Check [Anthropic Pricing](https://www.anthropic.com/pricing) for current rates
- Monitor your usage in the Anthropic Console

## Troubleshooting 🔧

### "Please set your Anthropic API key" Error
- Make sure you've replaced `YOUR_API_KEY_HERE` in `script.js`
- Check that your API key is correct and active
- Ensure there are no extra spaces or quotes

### File Upload Not Working
- Check that you're uploading supported formats (images: JPG, PNG, etc.; documents: PDF)
- Ensure the file size is reasonable (under 10MB recommended)
- Try a different file if one doesn't work

### API Errors
- Verify your API key is valid and has sufficient credits
- Check your internet connection
- Look at the browser console (F12) for detailed error messages

### Slow Response Times
- Large files (especially PDFs) take longer to process
- Complex medical reports require more analysis time
- Check your internet connection speed

## Browser Compatibility 🌐

Tested and working on:
- ✅ Google Chrome (recommended)
- ✅ Mozilla Firefox
- ✅ Microsoft Edge
- ✅ Safari

## Privacy & Security 🔒

- All communication with the API is encrypted (HTTPS)
- Your API key should never be shared publicly
- Medical information is sent to Anthropic's servers for processing
- No data is stored by this application (everything is processed in real-time)
- Consider privacy implications before uploading sensitive medical documents

## Customization 🎨

### Change Colors
Edit `styles.css` and modify the `:root` variables:
```css
:root {
    --primary-color: #2563eb;  /* Main blue color */
    --secondary-color: #10b981; /* Green accent */
    /* ... other colors ... */
}
```

### Modify AI Behavior
Edit the `SYSTEM_PROMPT` in `script.js` to change how the AI responds and what it focuses on.

### Adjust Max Response Length
In `script.js`, find this line and change the value:
```javascript
max_tokens: 4096,  // Increase for longer responses
```

## Support & Resources 📚

- **Anthropic Documentation**: https://docs.anthropic.com/
- **Claude API Reference**: https://docs.anthropic.com/claude/reference/
- **Anthropic Console**: https://console.anthropic.com/

## License 📄

This is a demonstration project. Feel free to modify and use it for your personal or commercial projects.

## Contributing 🤝

Suggestions and improvements are welcome! This is a template project designed to be customized for your specific needs.

---

**Made with ❤️ for better health awareness**

Remember: Your health is important. Use this tool as a supplement to, not a replacement for, professional medical care.
