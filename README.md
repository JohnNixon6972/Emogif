# Emogif

[![Netlify Status](https://api.netlify.com/api/v1/badges/404c3c08-e36d-49ea-b13b-ca539604aaff/deploy-status)](https://app.netlify.com/sites/emogif-jbn/deploys)
emojis into gif, just as the repo name states

## Prerequisites

To use this website the following is what you'll have to do.

* Clone this repository, or download it into your local machine.
* Download the `Web Server for Chrome` web app from [here](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb).
* Lauch the same application. This can be done by searching for the same using [this link](chrome://extensions/).
* Change the hosting folder to the downloaded folder of the repo.
* Access the Web Server URL as provided by the `Web Server for Chrome`.

And. There is one more even easier way to access it. Just click on [this hyperlink.]()

## Why this ?

This model was created because of one [John Nixon](https://github.com/JohnNixon6972) who wanted to use multiple emojis in sequence, to easily convey with others. So, thus incepted the idea of making gifs out of the emojis typed out.

## How this ?

The tech stuff used are as follows:

1. [JoyPixels](https://www.joypixels.com/) to convert the emoji to images, and it also lets you convert `:smile:` to 😄.
2. [GifShot](https://github.com/yahoo/gifshot) to convert the images into a gif.
3. [ImageMagick](https://imagemagick.org/index.php) to remove the white background of all the emoji images with the following command. 
```
cd assets
for i in *.png; do convert -flatten $i $i; done
```

## Contributing
To contribute, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <user_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

## Contact

Please use the [issues](https://github.com/JohnNixon6972/Emogif/issues) section to list down your queries. We will get back to you as soon as possible.

**Have a great day :)**
