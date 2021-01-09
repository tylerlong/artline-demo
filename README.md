# artline-demo

How to run?

1. `pip3 install -r requirements.txt`
2. `python3 app.py`

How to use?

1. Run the Flask app
2. Open `localhost:5000` in browser
3. Select an image( .png or .jpg ) then click `Go Art`
4. Once the process done successfully, you should see the result in browser.

Enjoy and give a star if you like it.


## Docker


```
wget https://github.com/jwenjian/artline-demo/releases/download/v0.1.0/ArtLine_650.pkl
docker build -t altline-demo:latest .
docker run -it --rm -p 5000:5000 altline-demo
```