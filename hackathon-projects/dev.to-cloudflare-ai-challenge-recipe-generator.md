# Dev.to Cloudflare AI Challenge: Recipe Generator

<figure><img src="../.gitbook/assets/hummingbird-cake.png" alt=""><figcaption><p>Cloudflare Generative AI Dev.to Hackathon</p></figcaption></figure>

Click on links to run the application and view the code:

{% include "../.gitbook/includes/untitled (5).md" %}

{% include "../.gitbook/includes/untitled (4).md" %}

### Description

[Dev.to](https://dev.to/) is a website where developers use blogs to share ideas and code.  Dev.to sponsors hackathons with its partners.

I created a web application that shares text and pictures for recipes. I used Cloudflare models to generate streaming text for the recipe and an image generator to visualize what the recipe might produce.

### Tools/Technology

This application was created for a [dev.to challenge](https://dev.to/challenges/cloudflare). It uses two Cloudflare models that were available at the time:&#x20;

* Chat: @hf/thebloke/llama-2-13b-chat-awq
* Image Generator: @cf/bytedance/stable-diffusion-xl-lightning
