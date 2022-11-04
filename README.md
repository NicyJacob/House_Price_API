# House_Price_API
First API deployed on Render

##Docker usage

In order to use this with Docker, you need to:
1. Build the image
Give your image with the name of you choice, here I used "docker-ml-model"
docker build -t docker-ml-model .

2. Run the image
docker run -t docker-ml-model

3. Try it!
You can now try your API at: http://172.17.0.2:5000/
Alternatively, you can also try on https://house-price.onrender.com/
