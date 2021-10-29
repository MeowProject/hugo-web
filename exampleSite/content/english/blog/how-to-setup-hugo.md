+++
author = " ゆうと "
date = 2021-10-28T16:00:00Z
description = "Tutorials how to setup hugo by meowcode!"
image = "/images/howtosetuphugo.png"
image_webp = "/images/howtosetuphugo.webp"
title = "How To Setup Hugo"

+++
## Install hugo by following those simple steps:

### STEP-1 : Hugo installation

Check this link below for install hugo on your computer. [hugo install documentation](https://gohugo.io/getting-started/installing/)

### STEP-2 : Create your project

Hugo provides a `new` command to create a new website.

$hugo new site meowcode ( You can replace meowcode with your project name)

### STEP-3 : Install the theme

You can search theme in [here](https://hugothemesfree.com/)

Also You can make your theme too!

$cd theme && hugo new theme

### STEP-4 : Host locally

Launching the website locally by using the following command:

    hugo server

Go to `http://localhost:1313`

### STEP-5 : Basic configuration

When building the website, you can set a theme by using `--theme` option. However, we suggest you modify the configuration file (`config.toml`) and set the theme as the default.

![](https://cdn.discordapp.com/attachments/689337226123149336/903504952679354478/unknown.png)

### STEP-6 : Create your first content pages

`hugo new blog/post-name.md`

Also You can use [forestry](https://forestry.io/)

### STEP-7 : Build the website

When your site is ready to deploy, run the following command:

\`hugo

# You can also create a minified version by using this command:

hugo--minify\`

A `public` folder will be generated, containing all static content and assets for your website. It can now be deployed on any web server.
