# Convolutional Neural Network Application (CNN) for reading handwritten numbers

------------

## Number Reader

#### It is a real-time number reader. It can be used on the cell phone or on the computer. Just draw with your finger or mouse in the area designated for it the number you want to read. It does everything in the browser using Tensorflow.js, based on a trained Python model with Tensorflow. You can see the CNN model <a href="https://colab.research.google.com/drive/1uLbxgbV9t53UlmMwnYBY1m7t030Tz0QP" target="_blank" rel="noopener noreferrer">here</a>.

### How to use

#### Download the repository wherever you like on your computer

#### Start a server in the folder.
This project uses a Tensorflow.js model, which to load requires access via http / https.
For that you can use any server, but here is a way to do it
- Download Python on your computer
- Open a command line or terminal
- Navigate to the folder where you downloaded the repository
- Execute the command:
```
    python -m http.server 8000 // port example
```
- Open a browser and go to http://localhost:8000 (if you have chosen that port)

#### You can also deploy the application on a static file server.

### More info. To see in:
- <a href="https://github.com/rramosp/2021.deeplearning" target="_blank" rel="noopener noreferrer">Fundamentos de Deep Learning</a>
- <a href="https://rramosp.github.io/2021.deeplearning/intro.html" target="_blank" rel="noopener noreferrer">Fundamentos de Deep Learning</a>
- <a href="https://www.youtube.com/playlist?list=PL8ytk70JVz1-YmW2YnFFDMroi_ZSggFgn" target="_blank" rel="noopener noreferrer">Fundamentos de Deep Learning (Youtube)</a>
- <a href="https://youtu.be/JpE4bYyRADI?t=350" target="_blank" rel="noopener noreferrer">Exportación de este modelo a JS con Tensorflow.js (Youtube)</a>
