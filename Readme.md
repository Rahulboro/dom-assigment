# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

### Output

![Output](./Pic2.png)

### SOLUTION 
     - document.querySelector(".crayons-subtitle-2").innerHTML= "ujjal"
     'ujjal'
     - document.querySelector(".color-base-70").innerHTML= "I write code"
     'I write code'
## SOLUTION SCREENSHOT 
![solution](./screenshots/1.jpg)

2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Picture_3.png)

### Fetch all the product name and store in an array

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

### SOLUTION
     -let productarray = document.queryselector(".global-menu-list").innerText
     -let newarray = []
     for (let i = 0; i < productarray.length; i++){
          newarray.push(productarray[i].textContent);
     }
     console.log(newarray)

![array](./screenshots/2.jpg)

3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)


### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

### Output

![Output](./Pic5.png)

### SOLUTION
     -let value 

![Solution](./screenshots/3.jpg)

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./Pic6.png)

### Tasks

      Change the contact number

### Output

![Output](./Pic7.png)
### SOLUTION 
     - let oneplustext = document.querySelector(".customer-support").innerText = "ujjal moni bordoloi"

![SOLUTION 4](./screenshots/4.jpg)

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out

### Output

![Output](./Pic9.png)
### SOLUTION
     - document.querySelector(".buynow a").innerText = "checkout"
![solution](./screenshots/5.jpg)

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

### Output

![Output](./Pic11.png)

### SOLUTION 
     - let searchtext = document.querySelector("._wrapper_1f3oz_1")
     searchtext.addEventListener('onmouseover', function redcolor() {document.body.querySelector("._wrapper_1f3oz_1").style.backgroundColor = redcolor
    })
7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### Output

![Output](./Pic13.png)

### SOLUTION 
     -  document.querySelector("#hp-search-input").value = "Search"
     document.querySelector("#hp-search-form").submit()
![SOLUTION](./screenshots/7.jpg)

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Output

![Output](./Pic15.png)

### SOLUTION 
     -let array = document.querySelectorAll('#SIvCob a')
     for (i=0; i < array.length; i++){
          if (i % 2 == 0 ){
               array[i].remove()
          }
     }:

![SOLUTION](./screenshots/8.jpg)

9. Webiste Name: [Code Wars](https://www.codewars.com/)
                                                                                                              
### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./Pic16.png)

### Tasks


    Change the font family of the text to monospace and text color to the logo’s background color.

### Output

![Output](./Pic17.png)
### SOLUTION 
     - let setcolor = document.querySelector(".text-align-center h1")
     setcolor.style.color = '#FF4D4D'

![solution](./screenshots/9.jpg)

10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

### Output

![Output](./Pic19.png)
### SOLUTION
     - document.querySelector('.col-lg-offset-2 .login-btn-text').addEventListener("mouseover", function () { document.querySelector('.col-lg-offset-2 .login-btn-text').style.backgroundColor = "red"
    
})
![SOLUTION](./screenshots/10.jpg)

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Output

![Output](./Pic21.png)
### SOLUTION 
     -document.querySelector('.wrapper a').style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')";
![SOLUTION](./screenshots/11.jpg)

12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./Pic22.png)

### Tasks

     change the background colour of the button to blue.

### Output

![Output](./Pic23.png)
### SOLUTION 
     -document.querySelector('.js-repos-container h2 a').style.backgroundColor = "Blue"
![SOLUTION](./screenshots/12.jpg)

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### Output

![Output](./Pic25.png)
### SOLUTION 
     -document.querySelector(".home22-intro-text p").innerText = "JSBOOTCAMP"
![SOLUTION](./screenshots/13.jpg)

14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

### Output

![Output](./Pic27.png)
### SOLUTION 
     - document.querySelector(".HotDealsAll__HotCampaignsEventsContainer__FK0V2 .HotDealsAll__Heading__2fIbe").style.fontSize = "80px"
![SOLUTION](./screenshots/14.jpg)
15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

### Output

![Output](./Pic29.png)
### SOLUTION 
     -document.querySelector(".ps-title").style.textAlign = "right"
![SOLUTION](./screenshots/15.jpg)

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Pic30.png)
### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### Output

![Output](./Pic31.png)
### SOLUTION
     -document.querySelector(".geist-wrapper .section-title_title__VEDfK").innerText = "Start With Scratch"

![SOLUTION](./screenshots/16.jpg)

17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./Pic33.png)

### Tasks

     change the button text To current Date.

### Output

![Output](./Pic32.png)
### SOLUTION
     -let changeDate = new Date; document.querySelector('.btn-container').innerHTML = changeDate;
![SOLUTION](./screenshots/17.jpg)

18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./Pic34.png)

### Tasks

    change the background colour blue to orange

### Output

![Output](./Pic35.png)
### SOLUTION
     -document.querySelector('.p-f03v2__footer').style.backgroundColor = 'orange' ;
![SOLUTION](./screenshots/18.jpg)

19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./Pic36.png)

### Tasks

    extract the canon logo

### Output

![Output](./Pic37.png)
### SOLUTION 
     -let srclink = document.querySelector('.navbar-brand').innerHTML; 
     console.log(srclink);
![SOLUTION](./screenshots/19.jpg)

20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./Pic38.png)

### Tasks

      Change the description colour black to orange

### Output

![Output](./Pic39.png)
### SOLUTION
![SOLUTION](./screenshots/20.jpg)
