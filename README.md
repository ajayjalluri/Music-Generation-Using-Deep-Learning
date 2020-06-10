# Music-Generation-Using-Deep-Learning
## Real World Problem
This case-study focuses on generating music automatically using Recurrent Neural Network(RNN). 
We do not necessarily have to be a music expert in order to generate music. Even a non expert can generate a decent quality music using RNN.
We all like to listen interesting music and if there is some way to generate music automatically, particularly decent quality music then it's a big leap in the world of music industry.
__Task__: Our task here is to take some existing music data then train a model using this existing data. The model has to learn the patterns in music that we humans enjoy. Once it learns this, the model should be able to generate __new___ music for us. It __cannot simply copy-paste__ from the training data. It has to understand the patterns of music to generate new music. We here are not expecting our model to generate new music which is of professional quality, but we want it to generate a __decent quality music__ which should be __melodious__ and __good to hear__.
Now, what is music? In short music is nothing but a __sequence of musical notes__. Our __input__ to the model is a sequence of musical events/notes. Our __output__ will be new sequence of musical events/notes. In this case-study we have limited our self to single instrument music as this is our first cut model. In future, we will extend this to multiple instrument music.
## Many-to-Many RNN
![alt text](https://miro.medium.com/max/1400/1*PinsNtKyu-b8EhHz-VR3Tg.png)
## Generating music
![alt text](https://miro.medium.com/max/1400/1*pPo4rXle7ttifQajRwMIgw.png)
## Data Source:
1. http://abc.sourceforge.net/NMD/
2. http://trillian.mit.edu/~jc/music/book/oneills/1850/X/

__From first data-source, we have downloaded first file:__
* Jigs (340 tunes)
## Type of Data:
There are total of 340 music tunes in abc notation.
## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.
3. keras
## Built With
* ipython-notebook - Python Text Editor
* numpy - numerical computation python library
* Keras - Deep Learning Library
## Mentor
* Thesis project under professor Soharab Hossain .
* https://www.linkedin.com/in/soharab/
## References
* https://www.appliedaicourse.com/
* https://en.wikipedia.org/wiki/ABC_notation
* https://abcjs.net/abcjs-editor.html
* https://medium.com/artists-and-machine-intelligence/neural-nets-for-generating-music-f46dffac21c0
* https://medium.com/datadriveninvestor/music-generation-using-deep-learning-85010fb982e2

