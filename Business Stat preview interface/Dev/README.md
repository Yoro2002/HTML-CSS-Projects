# Business Stats Preveiw Interface

## Description
This projects gives a better knowledge and experience on how media queries work for better responsiveness for all screen sizes and how to properly group some elements for accurate flexbox styling. And this project continues to test and improve your basic knowledge of HTML5, and CSS.

## Table of Contents
1. Installation
2. My Process
    - Built with
    - What i learned newly
    - Continued development 
3. Author 

## Installation
Using the npm package installer, I installed the latest version of Bootstrap through my Terminal
    npm install Bootstrap@5.3.3
- [Bootstrap](https://getbootstrap.com/) - Frontend Framework 

## My Process

### Built with
- Semantic HTML5 markup
- CSS custom properties in SCSS
- Flexbox
- Desktop-first workflow
- [Bootstrap](https://getbootstrap.com/) - Frontend Framework

### What I learned newly
 I have mastered the use of media queries to make responsive designs for all screen sizes.
 And I mastered the proper way to group the set of elements in HTML5 for accurate flexbox styling.

```css
 @media (max-width: 1000px) {
    .details h1 {
        font-size: var(--mobile-font-size-1);
    }
}

@media (max-width: 950px) {
    .details h1 {
        font-size: var(--mobile-font-size-2);
    }

    .details {
        width: 530px;
        height: 406px;
    }

    .image video {
        width: 530px;
        height: 406px;
    }
}

@media (max-width: 900px) {
    .details h1 {
        font-size: var(--mobile-font-size-3);
    }
}

@media (max-width: 890px) {

    body {
        display: flex;
        flex-direction: column-reverse;
    }

    .details {
        border-radius: 0 0 10px 10px;
    }

    .image video {
        border-radius: 10px 10px 0 0;
    }

    .details h1 {
        font-size: var(--mobile-font-size-1);
        text-align: center;
    }

    .details #moreInfo {
        text-align: center;
    }
}

@media (max-width: 600px) {

    .details {
        width: 326px;
        height: 426px;
        padding: 20px 20px 20px 20px;
    }

    .details h1 {
        font-size: var(--mobile-font-size-4);
    }

    .image video {
        width: 326px;
        height: 206px;
    }

    .details #moreInfo {
        text-align: center;
        margin-bottom: 30px;
    }

    .flex-box {
        display: flex;
        flex-direction: column;
        text-align: center;
    }
    
}
```
```html
<div class="flex-box">
            <div>
                <p class="margin-shift">30k+</p>
                <p class="bottom-style">COMPANIES</p>
            </div>

            <div>
                <p class="margin-shift">450</p>
                <p class="bottom-style">TEMPLATES</p>
            </div>

            <div>
                <p class="margin-shift">15M+</p>
                <p class="bottom-style">QUERIES</p>
            </div>
</div>
```

### Continued development
I will like to continue improving on the use of media queries and the proper use of flexbox and i would also like to study the use of grid css property.

## Author
- Website - [My Name Here](https://www.your-site.com)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


