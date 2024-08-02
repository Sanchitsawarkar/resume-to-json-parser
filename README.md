# Resume to JSON Parser using ChatGPT

## Prompt

Please parse the following resume content and convert it into the specified JSON format:

Sanchit Sawarkar
Email: sanchitsawarkar31@gmail.com
Phone: +9767373988
Location: Pune, India

Education

Vishwakarma Institute of Technology, Pune, India (Dec 2021 – Present)
Bachelor of Engineering in Electronics & Telecommunication Engineering, CGPA: 8.34
Jai Bajrang Junior College Alanda, Akola, India (2020)
Senior Secondary Education, Percentage: 77.85%
Prabodhan Vidyalaya, Daryapur, Amravati, India (2018)
Higher Secondary Education, Percentage: 94.60%
Technical Skills

Programming Languages: Java, Python, C, C++, R
Databases: SQL
Web Technologies: Graphic design, HTML, CSS, PHP, MySQL, JavaScript
Tools: Git, Android Studio, XXAMP server, Arduino UNO, VScode, Gen AI
Soft Skills: Problem Solving, Photography
Projects / Open-Source

Retinopathy Detection System with AI (RetinAI): Developed an AI-driven system for the detection of retinopathy using deep learning techniques. Utilized Python, TensorFlow, and OpenCV for model development and image processing.
AI Recommending IPC Based on Complaint: Collaborated on a legal AI project for the Smart India Hackathon. Implemented an AI system recommending Indian Penal Code (IPC) sections based on user complaints.
AI-Based Recommendation System Using Fuzzy Algorithm: Implemented an AI-based recommendation system leveraging fuzzy algorithms to enhance decision-making accuracy and provide personalized recommendations.
Bluetooth Controlled Wheelchair: Implemented a wheelchair control system utilizing Arduino Uno and Bluetooth technology.
Cab Services Price Comparison App: Developed an app for comparing OLA and UBER cab fares, providing users with cost-effective transportation options.
Gesture Vocalizer using IoT: Designed an IoT device interpreting finger movements to generate and display messages on an LCD screen.
Blink Control Wheelchair (Patent Published): Successfully patented a blink-controlled wheelchair system, enhancing accessibility for individuals with mobility challenges.
MERNifier (IIT Bombay Hackathon): Developed project, "MERNifier," during the IIT Bombay Hackathon. Leveraged advanced AI features for React and Node.js, enhancing code snippets generation, code compilation, and testing processes.
Extracurriculars

Photography Club Experience (2022-23): V-click official photography club of VIT Pune
Vatsalya Volunteer (2022-23): Volunteered in Vatsalya, a social awareness program. It includes visiting an old age home.
Format:
{
  "personal_information": {
    "name": "Your Name",
    "email": "Your Email",
    "phone": "Your Phone",
    "location": "Your Location"
  },
  "education": [
    {
      "institution": "Institution Name",
      "location": "Location",
      "degree": "Degree",
      "start_date": "Start Date",
      "end_date": "End Date",
      "cgpa": "CGPA"
    },
    ...
  ],
  "technical_skills": {
    "programming_languages": ["Language1", "Language2"],
    "databases": ["Database1"],
    "web_technologies": ["Tech1", "Tech2"],
    "tools": ["Tool1", "Tool2"],
    "soft_skills": ["Skill1", "Skill2"]
  },
  "projects": [
    {
      "name": "Project Name",
      "description": "Project Description"
    },
    ...
  ],
  "extracurriculars": [
    {
      "activity": "Activity Name",
      "organization": "Organization",
      "year": "Year",
      "description": "Activity Description"
    },
    ...
  ]
}

## Example Input

 
