# set proxy and then build & start
npm config set proxy http://localhost:8899
npm config set https-proxy http://localhost:8899

npm install --legacy-peer-deps
npm run build
npm run start

# pack it
npm run pack
