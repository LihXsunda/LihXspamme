pkg update
pkg upgrade
pkg install git -y
pkg install nodejs -y
pkg install yarn -y

git clone https://github.com/REYHAN6610/pairing_spam
cd pairing_spam
yarn install
npm start
