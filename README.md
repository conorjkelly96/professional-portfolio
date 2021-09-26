# Welcome to my Professional Portfolio

## About the project

This project consists of creating and designing my own webpage displaying links to my current GitHub repositories, social media links and an about me section. Furtherdown in this README you will find links to my professional portfolio. 

## Technologies Used

- HTML
- CSS
- BOOTSTRAP

## Link to GitHub Pages

[Click here!](https://conorjkelly96.github.io/professional-portfolio/)

### Solution Overview

## HTML Code

The structure of the website consisted of a variety of elements, most of which contained images, icons and text which needed formatting.

I decided to use [BOOTSTRAP](https://getbootstrap.com/) to gain inspiration for high quality card designs. The below is an example of modifications to the bootstrap card style used in this project.

```
<div class="card">
          <div>
            <img
              class="project-snapshot"
              src="./assets/images/demandplanning.jpeg"
              alt="Card image cap"
            />
          </div>
          <div class="project-body">
            <h5 class="card-title">Demand Planning</h5>
            <p class="card-text">Python | R</p>
          </div>
        </div>
```

### CSS Code

## Class Combinators

Class Combinators were used, in particular the descendant selector, to group CSS properties in aim to keep the code clean and concise.

```
.main-content,
.latest-project,
.card-content {
  margin: 48px;
}

```

CSS Variables for the background colors of the <header> and <footer> tags, alongside the the `.card` layout were used to keep the code tidy. The background color was created using [COLORSPACE](https://mycolor.space/). 

```
/* Declaring CSS variables */
:root {
  --pic-width: 150px;
  --pic-height: 100px;
  --backgroundcolor: linear-gradient(
    to bottom,
    #220952,
    #271466,
    #2a1f7b,
    #292b91,
    #2437a8,
    #223bb6,
    #1e3fc5,
    #1743d4,
    #273edd,
    #3638e4,
    #462fec,
    #5621f2
  );
}
```

## Final Website Structure

The layout of my professional portfolio is shown below:

![Original Website](assets/images/01-html-css-git-homework-demo.png)
