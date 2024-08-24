docker build -t scroller-position ./ 
docker run -it -v "$(pwd):/app" -p 3000:3000 scroller-position:latest bash 
npm start
