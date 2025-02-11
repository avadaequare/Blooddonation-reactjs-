React blood donation web app (It is present as a folder in below mentioned git hub so we follow below process instead of git clone)
git clone --no-checkout https://github.com/ianshulx/React-projects-for-beginners.git 
cd React-projects-for-beginners/
git sparse-checkout init --cone
git sparse-checkout set Blood_Donation_Website/client
git checkout

Install Node.js and npm
React applications require Node.js and npm (Node Package Manager).

🔹 Install on Ubuntu/Linux:

curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs
🔹 Install on Windows/Mac:
Download from Node.js Official Website
Verify Installation:

node -v
npm -v

npm start
npm run build
npm test

pm2 is a process manager that keeps apps running in the background
npm install -g pm2

Step 2: Start Your React App

pm2 start npm --name "react-app" -- start

Step 3: Check Running Apps

pm2 list

Step 4: Restart or Stop

pm2 restart react-app   # Restart  
pm2 stop react-app      # Stop  
pm2 delete react-app


<img width="942" alt="image" src="https://github.com/user-attachments/assets/00325e73-7499-4b0e-bf56-a5a2ecc2c062" />
