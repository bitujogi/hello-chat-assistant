Run the Project
1️⃣ Clone the Repository
git clone https://github.com/bitujogi/hello-chat-assistant.git
2️⃣ Go to the Project Folder
cd hello-chat-assistant
3️⃣ Install Dependencies
npm install
4️⃣ Create Environment File
Create a .env file in the project root.

nano .env

Add this:

GROQ_API_KEY=your_groq_api_key
PORT=5000
NODE_ENV=development
5️⃣ Start the Server
npx tsx server/index.ts

OR

npm start
6️⃣ Open the Application

Open your browser and visit:

http://localhost:5000


root@srv1422834:/var/www/Hello-Chat-Assistant# kill -9 $(lsof -t -i:5000)
root@srv1422834:/var/www/Hello-Chat-Assistant# cd /var/www/Hello-Chat-Assistant
root@srv1422834:/var/www/Hello-Chat-Assistant# tsx server/index.ts
10:24:05 AM [express] serving on port 5000
