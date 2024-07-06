![full_width](https://user-images.githubusercontent.com/51878265/156591618-0e95c2dc-862b-4769-a0c0-298be83a1d16.png)

## The following key problem statements are expected to be solved by participants:
---
### Project 1: Local Directory Video Transcription
*Objective*:
Develop a script to transcribe videos from a local directory, convert them to audio files, and generate a combined transcript.

*Repository*: https://github.com/ekatraone/local_transcription

*Steps*:
1. *Traverse Local Directory*:
   - Implement a script to recursively search and identify video files within a specified directory structure.
2. *Convert Videos to Audio*:
   - Utilize ffmpeg to extract audio tracks from identified video files, ensuring compatibility and quality.
3. *Transcription Using Whisper*:
   - Integrate Whisper for local audio transcription, leveraging its accuracy and efficiency in converting speech to text.
4. *Cooling Time Implementation*:
   - Incorporate intervals between transcription tasks to prevent system overheating, enhancing long-term stability.
5. *Generate Combined Transcript*:
   - Merge individual transcriptions into a cohesive transcript document, ensuring clarity and coherence.
6. *Create Datasets Using GPT-2*:
   - Develop scripts to generate diverse datasets in instruction, completion, and chat styles using GPT-2, facilitating model training.

*Tips and Potential Improvements*:
- *Error Handling*: Implement robust error handling mechanisms to manage file inconsistencies and transcription failures.
- *Performance Optimization*: Optimize script performance with parallel processing for faster directory traversal and transcription tasks.
- *Scalability*: Consider scalability options for handling large volumes of video files and transcripts efficiently.
---
### Project 2: YouTube Channel Transcription
*Objective*:
Create a script to transcribe videos from a specified YouTube channel, enhancing accessibility and searchability of content.

*Repository*: https://github.com/ekatraone/youtube_channel_transcription

*Steps*:
1. *Fetch Videos from YouTube Channel*:
   - Utilize YouTube Data API to retrieve video metadata and links based on the specified channel ID.
2. *Download Videos*:
   - Use youtube-dl tool to download videos locally, ensuring compliance with YouTube’s terms of service and API rate limits.
3. *Convert Videos to Audio*:
   - Employ ffmpeg for extracting audio from downloaded video files, ensuring uniformity in transcription inputs.
4. *Transcription Using Whisper*:
   - Implement Whisper for local transcription of audio files, ensuring high accuracy and minimal latency in generating text outputs.
5. *Generate Combined Transcript*:
   - Consolidate individual transcriptions into a unified document, maintaining chronological and contextual coherence.
6. *Create Datasets Using GPT-2*:
   - Develop diverse datasets in instruction, completion, and chat formats using GPT-2, enriching training data for AI models.

*Tips and Potential Improvements*:
- *Download Optimization*: Implement download resumption and error handling to manage interrupted downloads and ensure data integrity.
- *Quality Assurance*: Integrate validation checks for transcript accuracy and alignment with video content for enhanced usability.
- *Automation*: Explore automation tools for scheduled updates and new video processing to maintain content relevance.
---
### Project 3: Local LLM UI with Authentication and Weekly Email Report
*Objective*:
Develop a secure local UI with authentication features and automated email reporting for enhanced user interaction and data management.

*Repository*: https://github.com/ekatraone/local_llm_ui_with_authentication

*Steps*:
1. *UI Development*:
   - Design and implement a user-friendly interface using Flask/Django, ensuring intuitive navigation and accessibility.
2. *Authentication Feature*:
   - Integrate OAuth or similar authentication mechanisms to secure user access and protect sensitive data.
3. *Chat Log Feature*:
   - Implement local storage for chat logs, ensuring data encryption and compliance with privacy regulations.
4. *Weekly Email Report*:
   - Develop a scheduled task to compile and send weekly chat logs to designated email addresses, enhancing user engagement and transparency.

*Tips and Potential Improvements*:
- *Security Enhancements*: Implement SSL/TLS encryption for secure data transmission and storage, safeguarding user information.
- *User Feedback*: Incorporate feedback mechanisms to iterate UI/UX design based on user preferences and usability testing.
- *Integration Capabilities*: Explore API integrations for seamless data exchange with external systems, enhancing functionality and scalability.

---
### Project 4: Ask Catalyst
*Objective*:
Ask Catalyst utilizes ChatGPT technology trained on Catalyst 2030 website data to enhance member engagement and facilitate community collaboration via WhatsApp, leveraging the Mobius codebase.

*Repository*: https://github.com/ekatraone/askcatalyst

*Features*:
- *Respond to Member Inquiries*:
  - Provide detailed responses to member queries regarding Catalyst initiatives, goals, and community impact.
- *Partner Identification*:
  - Assist in identifying potential partners within the Catalyst network based on shared interests and objectives.

*Implementation*:
- *ChatGPT Integration*: Integrate ChatGPT for natural language processing and response generation.
- *WhatsApp Integration*: Utilize WhatsApp API for seamless communication and user engagement.

*Tips and Potential Improvements*:
- *Enhanced Personalization*: Implement user profiling to tailor responses based on member preferences and historical interactions.
- *Collaborative Filtering*: Introduce collaborative filtering techniques to suggest relevant partners and collaborations dynamically.
---
### Project 5: Grant Writing Support Tool
*Objective*:
The Grant Writing Support Tool leverages resources from the Social Change Innovators platform to aid grant writers within the Catalyst community, utilizing AI for enhanced user interaction and organization profiling.

*Repository*: https://github.com/ekatraone/Grant-Writing-Support-Tool

*Features*:
- *User Interface Development*:
  - Design an intuitive interface for users to access grant writing resources effectively.
- *Grant Proposal Assistance*:
  - Assist users in drafting grant proposals through interactive Q&A sessions, supporting voice, text, and file uploads.
- *Organization Profiling*:
  - Create detailed profiles of user organizations based on input data and interaction history.

*Implementation*:
- *AI Integration*: Integrate AI models for analyzing user inputs, generating tailored responses, and profiling organizations.
- *Voice Note Processing*: Implement voice note transcription and analysis to capture detailed information efficiently.

*Tips and Potential Improvements*:
- *Semantic Analysis*: Incorporate semantic analysis to refine question prompts and improve response relevance.
- *Scalability*: Design for scalability to handle increasing user base and data volume effectively.
---
### Project 6: Agri AI Chatbot on WhatsApp
*Objective*:
Develop a GPT-4.0 powered chatbot on WhatsApp to provide agricultural insights and facilitate bookkeeping tasks for farmers.

*Repository*: https://github.com/ekatraone/Agri-AI-Chatbot-on-WhatsApp

*Features*:
- *Bookkeeping Integration*:
  - Capture and categorize transaction data from receipts for simplified bookkeeping and financial management.
- *AI Tutoring*:
  - Provide agricultural insights and recommendations based on user queries, leveraging GPT-4.0 capabilities.

*Implementation*:
- *WhatsApp Interface*: Utilize WhatsApp API for interactive chatbot functionalities.
- *AI Backend*: Deploy GPT-4.0 models for natural language processing, bookkeeping integration, and agricultural expertise.

*Tips and Potential Improvements*:
- *Image Recognition*: Introduce image recognition capabilities for analyzing crop health and soil conditions from photos.
- *Real-time Updates*: Implement real-time updates on market prices and agricultural news to enhance user utility.
---
### Project 7: WhatsApp AI Tutor
*Objective*:
Build an AI tutor on WhatsApp using GPT-4.0 to provide interactive learning and support across text, image, and audio formats, with Whisper integration for audio transcription.

*Repository*: https://github.com/ekatraone/WhatsApp-AI-Tutor

*Features*:
- *Multi-format Interaction*:
  - Support text, image, and audio inputs for interactive learning sessions.
- *Whisper Integration*:
  - Enable audio transcription and analysis using Whisper technology for seamless user interactions.
- *GPT-4.0 Voice Output*:
  - Utilize GPT-4.0 for generating voice-based responses to enhance user engagement and learning effectiveness.

*Implementation*:
- *WhatsApp Integration*: Integrate with WhatsApp for broad accessibility and user engagement.
- *AI Backend*: Deploy GPT-4.0 models for natural language understanding and response generation.

*Tips and Potential Improvements*:
- *Personalized Learning Paths*: Develop personalized learning paths based on user progress and interests.
- *Feedback Mechanism*: Incorporate feedback loops to adapt responses and content based on user interactions.
---
### Project 8: AskShaperAI
*Objective*:
Develop AskShaperAI using ChatGPT technology tailored for the Global Shapers Community to enhance member engagement and support collaborative efforts, utilizing user profiles for enhanced partner recommendations.

*Repository*: https://github.com/ekatraone/AskShaperAI

*Features*:
- *Community Engagement*:
  - Provide responses to member inquiries about Global Shapers initiatives and community projects.
- *Partner Identification*:
  - Facilitate connections with potential collaborators within the Global Shapers network based on user profiles and interests.

*Implementation*:
- *ChatGPT Customization*: Customize ChatGPT for understanding specific Global Shapers topics and community dynamics.
- *RAG Integration*: Integrate with RAG (Retrieval-Augmented Generation) for improved partner search and recommendation.

*Tips and Potential Improvements*:
- *Dynamic Partner Matching*: Implement dynamic partner matching algorithms to suggest relevant connections in real-time.
- *Continuous Learning*: Incorporate continuous learning mechanisms to adapt to evolving community needs and member interactions.
---
### Project 9: Course-On-Prompt
*Objective*:
Course-On-Prompt is a dynamic project for people with limited data resources. Whether you’re an aspiring professional, a curious learner, or seeking continuous growth, Course-On tailors its approach to your unique needs.

*Repository*: https://github.com/ekatraone/course-on-prompt-v1_1.1

*Features*:
* Enrollment and Goal Setting:
  - You sign up on the platform, sharing your learning objectives like mastering a new programming language to understanding quantum mechanics. Course-On captures this information to create a customized learning journey.
* Daily Content Delivery:
  - Each day, you receive learning modules in various formats:
  - Text: Concise explanations, summaries, and key takeaways related to your chosen topics.
  - Audio: Narrated content for those who prefer auditory learning.
  - Images: Visual aids, infographics, and diagrams.
* Completion and Recognition:
  - Upon completing the entire course, you receive a personalized Certificate of Appreciation.
* Monitoring and Progress Tracking:
  - Detailed records of your activities like Module completion status, Time spent on each topic & Quiz scores are maintained.

---
### 10: Ask YC Combinator: 
*Objective*:
Ask Catalyst utilizes ChatGPT technology trained on YC Combinator website data to enhance member engagement and facilitate community collaboration via WhatsApp, leveraging the Mobius codebase.

*Repository*: https://github.com/ekatraone/ask_yc_combinator

*Features*:
- *Respond to Member Inquiries*:
  - Provide detailed responses to member queries regarding YC Combinator initiatives, goals, and community impact.
- *Partner Identification*:
  - Assist in identifying potential partners within the YC Combinator network based on shared interests and objectives.

*Implementation*:
- *ChatGPT Integration*: Integrate ChatGPT for natural language processing and response generation.
- *WhatsApp Integration*: Utilize WhatsApp API for seamless communication and user engagement.

*Tips and Potential Improvements*:
- *Enhanced Personalization*: Implement user profiling to tailor responses based on member preferences and historical interactions.
- *Collaborative Filtering*: Introduce collaborative filtering techniques to suggest relevant partners and collaborations dynamically.



