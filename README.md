# Module-1-Challange
Week 1 challange - Code Refactoring Assignment

## Description
In this activity we were tasked with refactoring the provided code of, Horiseon Marketing Website. The goal was to make improve the structure, readability and maintainability without altering the webpages' functionality. By reaching these goals, the code base now follows a more semantic structure which ultimately makes the website a lot for accessible. 

## Installation
To follow along and attempt at better refactoring the provided code start by:
1. Cloning the provided documents located in this <a href="https://github.com/coding-boot-camp/urban-octo-telegram.git">Github</a> repository.
2. Navigate to the relevant directory.
3. Open the "index.html" in your preferred browser.

Once the webpage has been loaded, take your time and explore the websites functionality and famliarise yourself with its layout. The end goal is now to adjust the provided code without it affecting how the webpage looks and its functionality, proceed carefully and attentively.

## Changes that were made

## HTML
- First, changes to the HTML file was made such as replacing the "<div>" element with relevant semantics such as tags like "header", "nav", "main", "section", "footer" and "figure". By making these changes the files' readability and structure was improved.
- ALT attributes were added to maximise the images accessibility and SEO.

## Original Header
```
   <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
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
        </div>
    </div>
```
## Refactored Header
```
<header class="container"> 
        <h1>Horiseon</h1>
        <nav class="text-right">
            <ul>
                <li><a href="#search-engine-optimization">Search Engine Optimization</a></li>
                <li><a href="#online-reputation-management">Online Reputation Management</a></li>
                <li><a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
```
## CSS
- Changes involving CSS had to do more with consolidating the class', by grouping them it reduced the repetitiveness of the code.
- By doing this is improves the readbility of the code and its efficiency, for example, if someone need to make changes to website visual design rather and rewriting the same elements multiple times by grouping the elements that share the same properties can be changed in tandem. 

## Original Code:
```
 .benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}
.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}
 .benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
```
## Refactored Code:
```
# .benefit-lead h3, .benefit-brand h3,.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}
```
## Contributions
Contributions are most welcomed, imrpovements and suggestions on areas that could have been done more efficiently is greatly appreciated. To do so: 
1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a PR

## Live Application
But clicking <a href="https://cbfcuh.github.io/Module-1-Challange/">here</a>, it will open to the webpage that has been refactored by me/

## Credits
Starter code was taken from https://github.com/coding-boot-camp/urban-octo-telegram















