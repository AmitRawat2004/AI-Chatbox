AI Chatbot with Google & Facebook Authentication + Privacy Mode


📌 Project Description


This AI-powered chatbot allows users to communicate with an intelligent assistant while offering secure login options and a privacy mode for enhanced security. Users can log in via Google, Facebook, or email, then choose between:


🔵 Normal Mode (saves chat history)
🔴 Privacy Mode (does not save conversations)


The chatbot is powered by OpenAI's GPT model, making it capable of natural, human-like conversations.


Features & Functionality



1️⃣ User Authentication (Google, Facebook, Email)



🔹 Users can log in using:


✅ Google OAuth (Google account)


✅ Facebook OAuth (Facebook account)


✅ Email & Password (stored securely in MySQL)


🔹 Spring Security & OAuth 2.0 will handle authentication.



2️⃣ Two Chat Modes



🔵 Normal Mode (Chat History Enabled)

✅ Stores user queries & AI responses in MySQL.

✅ Users can view their chat history after logging in.

✅ AI responses are fetched from OpenAI API.

🔴 Privacy Mode (Chat History Disabled)

✅ Messages are not stored in the database.

✅ Once the chat session ends, all data is erased.

✅ Users get temporary chat access.

3️⃣ AI-Powered Chat (OpenAI API Integration)



🔹 The chatbot will use OpenAI’s GPT model to generate intelligent responses.

🔹 The user types a query → The backend sends it to OpenAI API → The AI replies.

🔹 The response is displayed in the chat window.

4️⃣ Chat History (Only for Normal Mode)



🔹 Conversations are saved in MySQL and linked to each user.

🔹 Users can view old conversations when they log in.

🔹 If Privacy Mode is enabled, chat history is not stored.

5️⃣ User Profile & Settings



🔹 Users can update profile details (name, profile pic).

🔹 Users can toggle privacy mode before starting a chat.

🔹 Logout option available.

🔹 Tech Stack

✅ Backend: Java (Spring Boot, Spring Security)

✅ Frontend: JavaFX (Desktop) / React (Web UI)

✅ Database: MySQL (for user & chat storage)

✅ APIs Used:

Google & Facebook OAuth (User Authentication)

OpenAI API (AI Chatbot)
