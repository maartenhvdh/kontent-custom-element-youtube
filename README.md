# Youtube element

This Kontent.ai custom element allows you to add various types of youtube video url, it extracts and __stores__ the video id for your apps and shows the video.

![screenshot](https://assets-eu-01.kc-usercontent.com/a917b5bf-e2e1-011e-0a73-0b317b1e1c33/b383ecc3-601e-4716-a986-9aaf9e6ef623/custom-element-youtube.png)

## Setup

1. Deploy the code to a secure public host
   - See [deploying section](#Deploying) for a really quick option
1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
   - The `Hosted code URL` is where you deployed to in step 1
   - Pass the necessary parameters as directed in the [JSON Parameters configuration](#json-parameters) section of this readme.

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/hzik/kc_youtube/youtube.html)

## Configuration

You can specify the Parameters {JSON} part of the configuration to configure the default state or a lable.
Possible configurations:

```json
{
    "width": 800,
    "height": 600
}
```
