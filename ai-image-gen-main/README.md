# AI Image Generator

Utilizes the OpenAI API and the DALL-E model to generate original images based on user-provided text descriptions. The model is trained on the CIFAR-10 dataset and is able to generate a wide range of images, from photorealistic to highly stylized. The project also has a front-end interface built using React, allowing users to easily generate their own images.



## API

[OpenAI](https://openai.com/api/)

## Building

Alternatively you can download the code as a .zip file and extract it.

Install npm Package
`npm install`


To start a development enviroment use the following command.

```npm
npm start
```

If you want to add your own OpenAI API key do so by creating a .env file inside the root of the project.

```js
// Inside .env file
REACT_APP_API_KEY= = "yourKeyGoesHere";
```
