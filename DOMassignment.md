# 1. Webiste Name: [Dev To](https://dev.to/)
### Tasks
 Target the Top description div and change the DEV Community to <Your_Name> and description to your passion
### Sample Image

![Sample One](./images/Pic1.png)
### Output

![Output](./images/Pic2.png)


### Code:
``` javascript
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerText = "Meera Murthy"
document.querySelector(".side-bar .crayons-card .color-base-70").innerText = "Web developer / AI / Conversation designer"
```

![Results](./images/dom1.png)
![Results](./images/dom1b.png)
![Results](./images/dom1c.png)

# 2. Website Name: [Apple](https://support.apple.com/en-in)

### Topics
 - Get Element By Id, Create Element, Create Text Node, Append Child


### Tasks
  Add another FAQ 'My New FAQ' to the list

### Output

### Code:
```javascript
productlist = document.querySelectorAll(".as-imagegrid-item-title");
productlistarr = Array.from(productlist)
productlisttext = productlistarr.map(x=>x.innerText)
productlisttext1 = productlisttext.map(x=>x.split('\n')[0])
```

![Results](./images/dom2a.png)
![Results](./images/dom2b.png)
![Results](./images/dom2c.png)

# 3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child
### Sample Image

![Sample One](./images/Pic4.png)
### Output

![Output](./Pic5.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

### Code

```javascript
navnodelist = document.querySelectorAll("nav section.parent")
newele = navnodelist[7].cloneNode(true)
newele.querySelector("h3").setAttribute("aria-label", "My New FAQ")
newele.querySelector("h3").innerText = "My New FAQ"
document.querySelector("nav").appendChild(newele)
```

![Results](./images/dom3.png)
![Results](./images/dom3b.png)

# 4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText
### Sample Image

![Sample One](./images/Pic6.png)
### Output
![Output](./images/Pic7.png)


### Tasks

      Change the contact number

### Code

```javascript
document.querySelector(".one-tel-number").innerText = "+91 9999999999"
```

![Results](./images/dom4.png)

# 5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute
### Sample Image

![Sample One](./images/Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out

### Output
![Output](./images/Pic9.png)

### Code

```javascript
document.querySelectorAll(".diwali-deals-product-sale-btn")
btnlist = document.querySelectorAll(".diwali-deals-product-sale-btn")
Array.from(btnlist).map(x => x.innerText = "Check out")
```

![Results](./images/dom5a.png)
![Results](./images/dom5b.png)
![Results](./images/dom5c.png)

# 6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles
### Sample Image

![Sample One](./images/Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

### Output

![Output](./images/Pic11.png)

### Code
```javascript
function mouseover() { document.querySelectorAll("input")[0].style.backgroundColor = "red"; }
document.querySelectorAll("input")[0].setAttribute("onmouseover", "mouseover()")
function mouseOut() { document.querySelectorAll("input")[0].style.backgroundColor = "transparent" }
document.querySelectorAll("input")[0].setAttribute("onmouseout", "mouseOut()")
```

![Results](./images/dom6a.png)
![Results](./images/dom6b.png)
![Results](./images/dom6c.png)
![Results](./images/dom6d.png)

# 7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit
### Sample Image

![Sample One](./images/Pic12.png)


### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM
### Output

![Output](./images/Pic13.png)


### Code
```javascript
```

![Results](./images/.png)

# 8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./images/Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Output

![Output](./images/Pic15.png)

### Code
```javascript
document.querySelectorAll("#SIvCob a")
document.querySelectorAll("#SIvCob a")[0].remove()
```

![Results](./images/dom8.png)
![Results](./images/dom8a.png)


# 9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./images/Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

### Output

![Output](./images/Pic17.png)

### Code
```javascript
document.querySelectorAll(".display-heading-1")[0].style.color = "#b1361e"
document.querySelectorAll(".display-heading-1")[0].style.fontFamily = "monospace"
```

![Results](./images/dom9.png)

# 10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./images/Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

### Output

![Output](./images/Pic19.png)

### Code
```javascript
function mouseover() { document.querySelector(".btn-block .login-btn-text").style.backgroundColor = "red"; }
function mouseOut() { document.querySelector(".btn-block .login-btn-text").style.backgroundColor = "transparent" }
document.querySelector(".btn-block .login-btn-text").setAttribute("onmouseover", "mouseover()")
document.querySelector(".btn-block .login-btn-text").setAttribute("onmouseout", "mouseOut()")
```
![Results](./images/dom10.png)


# 11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./images/Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Output

![Output](./images/Pic21.png)

### Code
```javascript
document.querySelector(".logo").innerHTML = "<img width=\"100\" src=\"https://ineuron.ai/images/ineuron-logo.png\">"
```
![Results](./images/dom11.png)

# 12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./images/Pic22.png)

### Tasks

     change the background colour of the button to blue.

### Output

![Output](./images/Pic23.png)

### Code
```javascript
document.querySelector(".js-repo-form .btn").style.backgroundColor = "blue"
```

![Results](./images/dom12.png)

# 13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./images/Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### Output

![Output](./images/Pic25.png)

### Code
```javascript
document.querySelectorAll(".fl-heading-text")[0].innerText = "JSBOOTCAMP"
```

![Results](./images/dom13.png)

# 14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./images/Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

### Output

![Output](./images/Pic27.png)

### Code
```javascript
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "80px"
```
![Results](./images/dom14.png)

# 15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./images/Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

### Output

![Output](./images/Pic29.png)

### Code
```javascript
document.querySelectorAll(".ps-title")[4].style.textAlign = "right"
```
![Results](./images/dom15.png)

# 16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./images/Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### Output

![Output](./images/Pic31.png)

### Code
```javascript
document.querySelectorAll(".section-title_title__VEDfK")[0].innerText = "Start with Scratch"
```

![Results](./images/dom16.png)

# 17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./images/Pic33.png)

### Tasks

     change the button text To current Date.

### Output

![Output](./images/Pic32.png)

### Code
```javascript
document.querySelector(".retailer_btn-align").innerHTML = new Date()
```

![Results](./images/dom17.png)

# 18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./images/Pic34.png)

### Tasks

    change the background colour blue to orange

### Output

![Output](./images/Pic35.png)


### Code
```javascript
document.querySelector(".p-footer").style.backgroundColor = "orange"
```
![Results](./images/dom18.png)

# 19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./images/Pic36.png)

### Tasks

    extract the canon logo

### Output

![Output](./images/Pic37.png)

### Code
```javascript
document.querySelector(".logo").getAttribute("src")
```
![Results](./images/dom19.png)

# 20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./images/Pic38.png)

### Tasks

      Change the description colour black to orange

### Output

![Output](./images/Pic39.png)

### Code
```javascript
document.querySelectorAll(".desc")[0].style.color = "orange"
```

![Results](./images/dom20a.png)
![Results](./images/dom20b.png)
