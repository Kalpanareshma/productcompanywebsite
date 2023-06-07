# EX-07 Web Design for a Software Product Company
## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
## HTML:
## HOME PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KOLLYWOOD STATION</title>
    <link rel="stylesheet" href="./css/layout.css" />
  </head>
  <body>
    
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/home07.png" alt="Building" />
          <div class="contenttext">
            Welcome to our "KOLLYWOOD STATION"
            Here you can find your favourite movie posters, famous dialogues, customized phone cases
            <br />
             
            Each poster tells a story, enticing you to embark on a thrilling cinematic journey that transcends 
            the boundaries of the screen.
            <ul>
              <li>POSTERS</li>
              <li>CUSTOMIZED T-SHIRTS</li>
              <li>MOBILE CASES</li>
            </ul>
          </div>
          <DIV>
              Don't forgot to check out our new arrivals!!!
          </DIV>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by KALPANA S.
    </div>
  </body>
</html>

## PRODUCT PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FULLY FILMY</title>
    <link rel="stylesheet" href="./css/layout.css" />
    
  </head>

  <body>
    
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1 >Our Premium Products</h1>
          <h2 >MOVIE POSTERS</h2>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/POSTERR.png"  alt="product image">
                  </div>
                  <div class="itemname">OK KANMANI</div>
                  <div class="itemprice">Price: Rs.200 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/POSTER 2.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">VINNAI THAANDI VARUVAAYA</div>
                  <div class="itemprice">Price: Rs.199 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/gvm.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">ALAIPAAYUTHEY</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/GVM (2).jpeg"  alt="product image">
                  </div>
                  <div class="itemname">GVM</div>
                  <div class="itemprice">Price: Rs.333 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/JIGARTHANDA.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">SUPER STAR</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/minnale.png"  alt="product image">
                  </div>
                  <div class="itemname">MINNALE</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/96.png"  alt="product image">
                  </div>
                  <div class="itemname">96'</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/adukalam.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">ADUKALAM</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/anjali.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">ANJALI</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/super star.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">SUPER STAR</div>
                  <div class="itemprice">Price: Rs.399 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/vivek.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">VIVEK POSTER</div>
                  <div class="itemprice">Price: Rs.299 </div>
              </div>
              <h2>PHONE CASES</h2>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/APR.png"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.699 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/arrrr.png"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.499 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/u go man.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">VADIVELU DIALOGUE</div>
                  <div class="itemprice">Price: Rs.499 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/arp.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.599 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/arrr.png"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.599 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/arr.png"  alt="product image">
                  </div>
                  <div class="itemname">ARR</div>
                  <div class="itemprice">Price: Rs.599 </div>
              </div>
              
          </div>
          </div>
                  
      </div>
      <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by KALPANA S.
      </div>
    
  </body>
</html>
## PEOPLE PAGE:
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>KOLLYWOOD STATION</title>
        <link rel="stylesheet" href="./css/layout.css" />
    </head>
    <body>
            <div class="banner"></div>
            <div class="menu">
            <div class="menuitem"><a href="/static/home.html">Home</a></div>
            <div class="menuitem"><a href="/static/products.html">Products</a></div>
            <div class="menuitemselected"><a href="/static/people.html">People</a></div>
            <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
        </div>
        <div class="content">
        <div class="productcontent">    
        <h2 style="text-align:center;">PEOPLE</h2>
        <div class="productitems">
        <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/vetri.png"  alt="product image">
                  </div>
                  <div class="itemname">VETRI MARAN</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ram.png"  alt="product image">
                  </div>
                  <div class="itemname">RAM</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/thiagaraj.png"  alt="product image">
                  </div>
                  <div class="itemname">THIYAGARAJA KUMARARAJA</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/balu.png"  alt="product image">
                  </div>
                  <div class="itemname">BALU MAHENDRAN</div>
              </div>
              </div>
              </div>
    <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by KALPANA S.
    </div>                  
    </body>
</html>
## CONTACT US:
  <!DOCTYPE html>
<html lang="en">
    <head>
        <title>KOLLYWOOD STATION</title>
        <link rel="stylesheet" href="./css/layout.css" />
    </head>
    <body>
        <div class="banner"></div>
            <div class="menu">
            <div class="menuitem"><a href="/static/home.html">Home</a></div>
            <div class="menuitem"><a href="/static/products.html">Products</a></div>
            <div class="menuitem"><a href="/static/people.html">People</a></div>
            <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
        </div>
        <div class="content">
            <h1>CONTACT US</h1>
            <div class="contenttext">
            <h2>ADDRESS:</h2>
            <p>#42 ooty road</p>
            <p>Kodaikanal</p>
        </div>
        <div>
            <h2>EMAIL id: </h2>
            <p>kalpanareshma5@gmail.com</p>
            <p>kalpana@kollywoodstation.com</p>
        </div>
        <h2>CONTACT NUMBER</h2>
        <p>1235679040</p>
        <h2>You may also contact us through</h2>
        <p><strong>INSTAGRAM</strong> @kollywood_station</p>
        <p><strong>FACEBOOK</strong> @kollywood_station</p>
        <p><strong>LINKEDIN</strong> @kollywood_station</p>
        </div>
    <div class="footer">
        Copyright &#169; 2023 KOLLYWOOD STATION, Developed by KALPANA S.
    </div>
    </body>
</html>
  
## OUTPUT:
![exp71](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/a9b5134c-04e5-4808-b565-89c1c440941d)
![ep92](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/aa2720ed-9052-46fe-bdfd-487e825a5f89)
![exp93](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/8803a144-7e9c-473c-bfbe-79d5736d8677)
![exp74](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/b14117b9-685d-413b-89c0-cb7f0c559f7c)
![exp75](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/9d3123e1-340b-4208-9262-f2d2089db902)
![exp76](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/e3cc4558-a1ee-4466-8f48-9b606c3e5a8e)
![exp77](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/a88fb6d2-f6a5-44d6-9cca-8c7835829b15)
![exp78](https://github.com/Kalpanareshma/productcompanywebsite/assets/122040453/455bf19c-d92e-459b-adcc-8eca44d7487d)
## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
