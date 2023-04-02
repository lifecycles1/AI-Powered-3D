npm create vite@latest -- --template react client
cd client
npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
create server folder
cd server
npm init -y
add to "scripts" in package.json "start" : "nodemon index"
and add "type" : "module"
npm install cloudinary cors dotenv express mongoose nodemon openai
