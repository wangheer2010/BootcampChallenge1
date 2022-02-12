# 01 HTML, CSS, and Git: Code Refactor

## Purpose of the Assignment

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities and/or socio-economic restrictions have access to their website. Accessible websites are better optimized for search engines, and help companies avoid litigation.

I will build a codebase for a marketing agency that follows accessibility standards so that the site is optimized for search engines

## What I did

### 01 Semantic HTML Elements in The Source Code

- Changed the divs to ```header```, ```nav```, ```section```, ```aside```, ```footer```, ```figure```, etc. to make the elements semantic
- Removed the unnecessary  ```span``` in the h1 to make it clear

### 02 The Structure of The HTML Elements Follow a Logical Structure Independent of Styling and Positioning

- Changed the html and then changed the corresponding css rule to make it applies correctly
- Changed the improper classes and ids in the html to make it more specific
- Moved the link to the hero image from css to html and correctly set the size

### 03 The Icon and Image Elements Have alt Attributes

- Added alternative text attribute in every img element, including hero image

### 04 The Heading Attributes Fall in Sequential Order

- Changed the h2 in footer to h4
- Reasoning: I changed h2 to h4 for the header in footer because I think the header in the footer is not as important as the header in aside, which is h3. And they all are not as important as the header in the section, which is h2

### 05 The Title Element is Concise and Descriptive

- Changed the title to a decriptive and concise title __Horiseon official website__

## Screenshot

![How the webpage look like](./assets/images/screencapture-file-Users-chenwang-Desktop-msu-BootcampChallenge1-index-html-2022-02-12-12_42_55.png)

## Link
The link to my deployed website is [here](https://wangheer2010.github.io/BootcampChallenge1/)