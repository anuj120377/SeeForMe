# SeeForMe

### **Introduction and Motivation -**

The World Health Organization (WHO) has reported that approximately 285 million people are visually impaired worldwide, and out of these 285 million, 39 million are completely blind. It gets extremely tough for them to carry out daily activities, one of which is reading.

From reading a newspaper or a magazine to reading an important text message from your bank, it is tough for them to read the text written in it.A similar problem they also face is seeing and enjoying the beauty of pictures and images. Today, in the world of social media, millions of images are uploaded daily. Some of them are about your friends and family, while some of them are about nature and its beauty. Understanding what is present in that image is quite a challenge for certain people who are suffering from visual impairment or who are blind.

In this project, we will convert an image to text description first; then, using a simple text-to-speech API, we will extract the text description/caption and convert it to audio. So the central part is focused on building the caption/text description whereas the second part, which is transforming the text to speech is relatively easy with the text to speech API.

### **Objective -**

Create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset.
This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. The model will convert the contents of an image and will provide the output in the form of audio.

Steps Involved -
1. Traditional CNN-GRU model
2. Attention model
3. Text and Image preprocessing
4. Data Visualization using wordcloud
5. Model training and model evaluation (INCEPTIONV3)
6. Greedy search and BLeU Score

