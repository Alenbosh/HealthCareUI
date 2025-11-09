# HealthCareUI
# 💙 MindCare - AI Mental Health Support Chatbot

<div align="center">
  
![MindCare Banner](https://img.shields.io/badge/Mental%20Health-Support-89CFF0?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A compassionate AI chatbot designed to provide emotional support and crisis resources for mental health challenges**

[Live Demo](#) • [Features](#features) • [Installation](#installation) • [Contributing](#contributing)

</div>

---

## 🌟 Overview

MindCare is a responsive web-based AI chatbot specifically designed to support individuals dealing with mental health challenges including depression, anxiety, and suicidal thoughts. With a calming interface and empathetic responses, MindCare provides a safe space for users to express their feelings and access critical mental health resources.

> **⚠️ Important Notice**: This is an AI support tool and NOT a replacement for professional mental health care. If you're in crisis, please contact emergency services or call the National Suicide Prevention Lifeline at **988**.

---

## ✨ Features

### 🎯 Core Functionality
- **24/7 Availability** - Always accessible support when you need it
- **Crisis Detection** - Automatically identifies urgent situations and provides immediate resources
- **Quick Action Buttons** - Fast access to common mental health topics
- **Empathetic Responses** - Warm, non-judgmental conversation design
- **Resource Sharing** - Direct links to crisis hotlines and professional help

### 🎨 Design Highlights
- **Calming Color Palette** - Soft blues and pinks for a soothing experience
- **Fully Responsive** - Seamless experience on mobile, tablet, and desktop
- **Smooth Animations** - Gentle transitions that reduce anxiety
- **Accessible UI** - High contrast and readable typography
- **Typing Indicators** - Real-time feedback for engaging conversations

### 🆘 Safety Features
- **Prominent Crisis Banner** - Immediate access to emergency resources
- **Keyword Detection** - Identifies concerning language patterns
- **Professional Support Emphasis** - Encourages seeking qualified help
- **Confidentiality Notice** - Clear communication about privacy

---

## 📱 Screenshots

<div align="center">

### Mobile View
<img src="screenshots/mobile-chat.png" width="300" alt="Mobile Chat Interface">

### Desktop View
<img src="screenshots/desktop-view.png" width="600" alt="Desktop Interface">

### Crisis Response
<img src="screenshots/crisis-response.png" width="300" alt="Crisis Support">

</div>

---

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor (VS Code, Sublime Text, etc.)

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/Alenbosh/HealthCareUi.git
   cd mindcare-chatbot
```

2. **Open the application**
```bash
   # Simply open the HTML file in your browser
   open index.html
   # or
   start index.html
```

3. **That's it!** 🎉 No build process or dependencies required.

### Using a Local Server (Optional)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (http-server)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

---

## 🛠️ Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - No frameworks, lightweight and fast
- **Responsive Design** - Mobile-first approach

---

## 📋 Usage

### Basic Interaction
1. Type your message in the input field
2. Press Enter or click the send button
3. Receive supportive responses and resources

### Quick Actions
Use predefined buttons for common topics:
- 🆘 I need help now
- 😔 Feeling overwhelmed
- 💭 Depression struggles
- 😰 Anxiety support
- 🛠️ Coping strategies

### Crisis Support
Click the red crisis banner at the top for immediate access to:
- National Suicide Prevention Lifeline: **988**
- Crisis Text Line: Text **HOME** to **741741**
- International resources

---

## 🎨 Customization

### Changing Colors
Edit the CSS gradient variables in the `<style>` section:
```css
/* Main gradient */
background: linear-gradient(135deg, #89CFF0 0%, #9DB4C0 100%);

/* Crisis banner */
background: linear-gradient(135deg, #ff6b6b 0%, #ee5a6f 100%);
```

### Adding More Quick Actions
Modify the JavaScript to add custom buttons:
```javascript
<button class="quick-action-btn" onclick="sendQuickMessage('Your topic')">
  Your Button Text
</button>
```

### Integrating Real AI
Replace the `sendMessage()` function to connect with:
- OpenAI API
- Anthropic Claude API
- Google Gemini API
- Custom ML models

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Areas for Contribution
- [ ] Multi-language support
- [ ] Voice input/output
- [ ] Sentiment analysis
- [ ] Journal feature
- [ ] Mood tracking
- [ ] Integration with real AI APIs
- [ ] Accessibility improvements
- [ ] More coping strategy resources

---

## 🔒 Privacy & Security

- **No Data Storage** - Conversations are not stored or transmitted
- **Client-Side Only** - All processing happens in your browser
- **No Tracking** - No analytics or user tracking implemented
- **Open Source** - Full transparency in code

---

## 📚 Resources

### 🆘 Crisis Hotlines (India)

| Service | Phone | Hours | Description |
|--------|-------|-------|-------------|
| **AASRA** | **+91 9820466726** | 24/7 | Suicide prevention & emotional support |
| **Vandrevala Foundation** | **+91 9999 666 555** | 24/7 | Mental health crisis support |
| **iCall (TISS)** | **+91 9152987821** | Mon–Sat, 10AM–8PM | Professional counseling (inclusive & confidential) |
| **Fortis Stress Helpline** | **+91 8376804102** | 24/7 | Emotional wellness & counseling support |

If you prefer online search for local help:
**https://findahelpline.com**

---

### 🧠 Mental Health Organizations (India)

| Organization | Focus | Website |
|-------------|--------|---------|
| **The Live Love Laugh Foundation** | Depression & Anxiety Awareness, Therapist Directories | https://thelivelovelaughfoundation.org |
| **NIMHANS** | National Mental Health Institute & Helplines | https://nimhans.ac.in |
| **Mpower** | Counseling & Clinical Mental Health Services | https://mpowerminds.com |
| **Mann Talks** | Online Counseling and Mental Health Education | https://www.manntalks.org |
| **Parivarthan (Bangalore)** | Phone & Online Counseling Services | https://parivarthan.org |

---

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Inspired by the need for accessible mental health support
- Color palette designed for calming effects
- Crisis resources from national mental health organizations
- Community feedback and suggestions

---

## 📞 Contact & Support

- **Email**: Alenbosh@google.com

---

<div align="center">

### 💙 Remember: You're Not Alone

**If you or someone you know is in crisis, please reach out for help immediately.**

Made with 💙 by [Alen](https://github.com/Alenbosh)

**Star ⭐ this repo if you found it helpful!**

</div>
