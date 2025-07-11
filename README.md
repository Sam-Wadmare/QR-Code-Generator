QR Code Generator (Terminal-Based)
This is a simple Node.js project that generates a QR code image from user input directly in the terminal. It uses the inquirer package to get input and qr-image to create the QR code.

-Features
Get a URL from the user through terminal input

Generate a QR code image (qr_img.png)

Save the entered URL into a URL.txt file

-Getting Started
1. Clone the Repository
git clone https://github.com/your-username/qr-code-terminal.git
cd qr-code-terminal
2. Install Dependencies
npm install inquirer qr-image
3. Run the App
node solution.js

-Output
After running, the app will:
Create a qr_img.png (QR code image)
Create a URL.txt containing the entered URL
Both files will appear in your project directory.

📦 Dependencies
inquirer
qr-image
fs (built-in Node.js module)
