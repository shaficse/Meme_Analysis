# Meme Analysis
A meme is a combination of pictures and text which can be thought of as a risen medium for spreading ideas, values, behaviors, and cultures among the social networks. Usually, memes are created for humor but some of them are hateful.  A human can understand the meme considerably easily as human has the power to think about pictures and text together and draw a conclusion. For machine, it's quite hard to conclude a single decision by considering both text and pictures. Our idea is simple. First we converted the image into text by using attention based image to text generator.
Then we used a transformer based  language model to conclude final decision wherether the meme is offensive and non-offensive.


For Details unserstanding Please read the [document](https://github.com/shaficse/Meme_Analysis/blob/main/Internet%20Meme%20Analysis.pdf).


## Dataset
First I collected the Public Meme analysis dataset and then using Attention based Image to text generator model to generate text from the Meme images. After that, I used a language model for semi-annotating those text into offensive and non offensive categories. These semi-annotated text are further reviewed by human.
Finally, I prepared train, test, validation dataset from the reviewed text. For example, please check the sample of the training data:

```
image_name	                                                                            sentence	                                                  label
LJ3r8Gy.png	OFFICIAL BERNIE SANDERS DRINKING GAME ! Every time The Bernster mentions a free government program , chug somebody else 's beer ! 	Non-offensiv

```

## Dependency
```
python 3.7
tensorflow 2.x
matplotlib
sklearn
jupyter notebook
```
