# Horiseon Accessibility Project
*Optimizing an application for accessibility*

## Goal

To transform a visually complete web application into one which appears identical at the surface, but through the use of semantic elements and code consolidation, is easier to use for both visually impaired end-users and for future developers looking to improve upon this application.

## Purpose

Semantic elements make a web application easier to work with, both for the visually impaired and for future developers who may need to dive into the code in order to update content. For the visually impaired speifically, screen readers in use today require semantic elements in the HTML they analyze in order to properly convey the structure of the application to the end-user. Without these semantic elements, the user may find the webpage inaccessible.

## Method

While visually appealing, the webpage in its initial form was lacking in semantic HTML elements, opting to use < div > elements in many places where tags such as < section >, < header >, < article > would be more suitable to provide better semantic structure. These < div > elements were replaced with the aforementioned semantic elements where appropriate. In addition, much of the CSS styling contained redundant code which, after being condensed, will allow for future developers to more easily update their content. 

## Usage

### < header > tag replaced < div > tags here:

```md
![Header and Navigation](assets\images\Header.png)
```

### < section > container was used to hold each of the following three items and < article > tags were used for each individual item (where previously < div > tags had been used):

```md
![Search Engine Optimization](assets\images\SEO.png)
```

```md
![Online Reputation Management](assets\images\ORM.png)
```

```md
![Social Media Marketing](assets\images\SMM.png)
```

### < aside > container used for the aside element of the application, again in place of < div > tags:

```md
![Aside](assets\images\Aside.png)
```

## Credits

<ul>
    <li>Valerie Flores - Mentor and tutor || <a href="https://github.com/valeriemiller5">Github</a></li>
    <li>Guillermo Barila - General Github support || <a href="https://github.com/gui365">Github</a></li>
    <li>Samuel Maddox - General CSS support || <a href="https://github.com/SamuelMaddox">Github</a></li>
    <li>Tutorial on semantic HTML || <a href="https://www.w3schools.com/html/html5_semantic_elements.asp">w3schools.com</a>
</ul>

## License

MIT License

Copyright (c) 2021 Maxson Green

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.