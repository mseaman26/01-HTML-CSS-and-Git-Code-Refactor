# Refactored-HTML-and-CSS-for-Horiseon-Webpage-
I was given HTML and CSS code that needed to be refactored.  The code functioned fine and rendered a webpage for a digital marketing company called Horiseon

## Languages Used
This project primarily involved the HTML and CSS languages.  However we also used command line, git, and github for storing the project in a repository and github pages for deployment

## Methods Used
To refactor the HTML code, I looked for anything that looked out of place or redundant.  This involved eliminating unnecessary div tags, classes, and more. I also looked for any elements that did not read semantically. Many div tags could be replaced by another element such as main, section, footer, and more.

To refactor the CSS code, I similarly looked for anything that looked out of place or redundant.  I looked for repitition, particularly classes or elements that shared the exact same properties and values.  This also gave me a chance to see more HTML code that needed to be refactored

## An Example of some refactored HTML code

```html
    <!-- Got rid of an unnecessary <div>
    element add “header” class and simply made this a header tag -->
    <header>
        <!-- Made “seo” and ID rather than a class,
         because it is only used once 
        Also made sure the the header tags were in proper order, going from
        h1 to h2, h3 etc...-->
        <h1>Hori<span id="seo">seo</span>n</h1>
        <nav>
            <!-- eliminated an unnecessary <div. here, the <ul> 
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

```
## Author Links
[LinkedIn](https://www.linkedin.com/in/michael-seaman-120a59250/)
[GitHub](https://github.com/mseaman26)