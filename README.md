# Refactored-HTML-and-CSS-for-Horiseon-Webpage-
I was given HTML and CSS code that needed to be refactored.  The code functioned fine and rendered a webpage for a digital marketing company called Horiseon. My job was to refactor this code to make it as elegant, semantic, accessible, and as simple as possible without changing the look of the webpage at all.

## An Overview of How the Website Looks

![Horiseon](./assets/01-html-css-git-homework-demo.png)

## Languages Used
This project primarily involved the HTML and CSS languages.  However I also used command line, git, and github for storing the project in a repository and github pages for deployment

## Methods Used
To refactor the HTML code, I looked for anything that looked out of place or redundant.  This involved eliminating unnecessary \<div\> tags, classes, and more. I also looked for any elements that did not read semantically. All of the \<div\> tags could be replaced by other elements such as \<main\>, \<section\>, \<footer\>, and more.

To refactor the CSS code, I similarly looked for anything that looked out of place or redundant.  I looked for repetition, particularly classes or elements that shared the exact same properties and values with one another.  This also gave me a chance to see more HTML code that needed to be refactored

## An Example of some refactored HTML code

```html
    <!-- Got rid of an unnecessary <div>
    element and “header” class and simply made this a header tag -->
    <header>
        <!-- Made “seo” an ID rather than a class,
         because it is only used once.
        Also made sure that the header tags were in proper order, going from
        h1 to h2, h3 etc...-->
        <h1>Hori<span id="seo">seo</span>n</h1>
        <!-- This <nav> was originally a <div> . It is now more semantic  -->
        <nav>
            <!-- eliminated an unnecessary <div>. Here, the <ul> 
                is all we need -->
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
    <!-- This <img> was originally a <div> with a background image and with a 
    class “hero.” I figured it’s unnecessary to have it as a background 
    image because there’s nothing on top of it.  Plus it reads more 
    semantically this way -->
     <!-- added descriptive alt properties to this <img> 
            and to all the others in this file -->
    <img src="./assets/images/digital-marketing-meeting.jpg" id="hero" alt="Three men and one woman at a conference 
    table working on digital marketing">
```

## An Example of some refactored CSS code
```CSS
/* 
All three images in what is now the <main> portion shared this property, 
so the CSS could be consolidated here */
main img {
    max-height: 200px;
}
/* A lot of consolidation occurred in what is now the <aside>.  Many redundant selectors were
eliminated */
aside {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

aside section{
    margin-bottom: 32px;
    color: #ffffff;
}
```
## Other Goals for this project
- To further my understanding and grow my skillset in the above mentioned languages and technologies
- To better understand what a potential user would be looking for when viewing my future projects on github
- To give me a profound sense of accomplishment
<br>
<br>
## -By Michael Seaman

## Author Links
[LinkedIn](https://www.linkedin.com/in/michael-seaman-120a59250/)
[GitHub](https://github.com/mseaman26)

