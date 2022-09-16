# Turn Images To Videos Using Nodejs And Shotstack API

This program turns images to slideshow videos with music using Node js, [Shotstack Node SDK](https://www.npmjs.com/package/shotstack-sdk), and Shotstack API. See [this tutorial](https://shotstack.io/learn/turn-images-into-slideshow-video-nodejs/?utm_source=github&utm_campaign=demo_repos) to learn how it works.


### What is Shotstack API?

Shotstack API is a cloud based video editing API that enables you to render multiple videos concurrently in the cloud using your favourite programming language. Sign up for a free developer account [here](https://dashboard.shotstack.io/register?utm_source=github&utm_campaign=demo_repos) to get your API key. 

### Why use Shotstack API?

Rendering videos is a resource consuming process. It may take several minutes to render one video depending on the complexity of the video. Shotstack enables to concurrently render multiple videos in the powerful cloud infrastructure. This reduces rendering time and fastens the process. Visit our [Docs](https://shotstack.io/docs/guide/getting-started/core-concepts/?utm_source=github&utm_campaign=demo_repos) to learn more.

Checkout other video editing Node demo examples in this [Github repo](https://github.com/shotstack/node-demos).


### Installation

Clone this repository with following command

```bash
git clone https://github.com/shotstack-samples/images-to-videos-nodejs.git
```

Go inside the project directory
```bash
cd images-to-video-nodejs
```

Install the required dependencies including the [Shotstack Node SDK](https://www.npmjs.com/package/shotstack-sdk)

```bash
npm install
```


### Set your API key

The demos use the **staging** endpoint by default so use your provided **staging** key:

```bash
export SHOTSTACK_KEY=your_key_here
```

Windows users (Command Prompt):

```bash
set SHOTSTACK_KEY=your_key_here
```

You can [get an API key](http://shotstack.io/register?utm_source=github&utm_campaign=demo_repos) by signing up for a free developer account via the Shotstack web site.


### Running the program

To run this program, run the `images.js` inside the root folder:

```bash
Node images-to-videos-Node/images.js
```

### Final video example

[Here](https://d1uej6xx5jo4cd.cloudfront.net/basic-slideshow-nodejs.mp4) is what the final video looks like.

### Accessing rendered videos

To access your rendered videos, sign into your Shotstack account. Inside the dashboard, you can find all rendered videos under Renders tab.

![Alt Text](https://im5.ezgif.com/tmp/ezgif-5-9da1b35692.gif)


### Edit and automate video production using Node

This is just a basic example. You can do way more with Shotstack Node SDK like: 
- Beautify videos by adding effects, transitions, overlays, titles
- Automate video editing and production
- Personalize videos with code
- Convert media files i.e. gif, mp3, mp4, jpg, bmp, and png
- Generate, add SRT files to multiple videos concurrently
- Use AI to generate media assets to produce videos & more

See our other [tutorial articles](https://shotstack.io/learn/?utm_source=github&utm_campaign=demo_repos) to learn video editing using Node js. 