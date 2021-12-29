# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company .

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
~~~
HOME CODE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TCS Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/CCTV.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TCS Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/cctv.jpg" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br/>
            
            <ul>
              <li>can secure the area.</li>
              <li>can solve many crimes</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 TCS Private Limited, Developed by THIRU.G.
      </div>
    </div>
  </body>
</html>

PRODUCT CODE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TCS Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TCS Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV2.jpg" alt="product image">
                  </div>
                  <div class="itemname">DOME CAMERA-purpose is Video Surveillance in Retail Stores and Offices with mic.</div>
                  <div class="itemprice">Price: Rs.6,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">BULLET CAMERA-purpose is Long-distance surveillance up to 40 FtOutdoors weatherproof surveillance</div>
                  <div class="itemprice">Price: Rs.16,000.00 </div>
              </div>
             
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">C-MOUNT CAMERA-purpose is To achieve variable zoom in surveillance </div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>
            
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">DAY-NIGHT camera-pupose is For 24×7 surveillance Often in low light conditions</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div> 

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">PTZ camera -purpose is PTZ Cameras are to achieve responsiveness can rotate 360.degree, can zoom in and out. </div>
                  <div class="itemprice">Price: Rs.18,000.00 </div>
              </div>

               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">HIGH DEFINITION camera-purpose is At highly niche places HD CCTV cameras work well e.g., casinos and banks Casino managers often check if a player is counting cards or not through this camera </div>
                  <div class="itemprice">Price: Rs.21,000.00 </div>
              </div>
              
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV7.jpg"  alt="product image">
                  </div>
                  <div class="itemname">INFRARED NIGHT VISION camera-pupose is it can see clearly when lighting is poor or absolute darkness.</div>
                  <div class="itemprice">Price: Rs.18,000.00 </div>
              </div> 

               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV8.jpg"  alt="product image">
                  </div>
                  <div class="itemname">IP CAMERA works on wireless technology and pupose is to send recording over a far distance without requiring any power boost using a cable.</div>
                  <div class="itemprice">Price: Rs.28,000.00 </div>
              </div> 
               
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV9.jpg"  alt="product image">
                  </div>
                  <div class="itemname">SPY CCTV-its purpose is to spy an area without the knowledge of strangers.</div>
                  <div class="itemprice">Price: Rs.12,500.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV10.jpg"  alt="product image">
                  </div>
                  <div class="itemname">GATE INTERCOM-its purpose is to find and negiotiate with strangers by gate itself.</div>
                  <div class="itemprice">Price: Rs.35,500.00 </div>
              </div>
            
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV11.jpg"  alt="product image">
                  </div>
                  <div class="itemname">WEB CAMERA-purpose is to make a video presentations through any online platforms.</div>
                  <div class="itemprice">Price: Rs.2,400.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/CCTV12.jpg"  alt="product image">
                  </div>
                  <div class="itemname"> RECOGNIZER camera-it works on advanced intelligence to recognize strangers through their eyes.</div>
                  <div class="itemprice">Price: Rs.82,400.00 </div>
              </div>

          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 TCS Private Limited, Developed by THIRU.G.
      </div>
    </div>
  </body>
</html>

PEOPLE CODE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TCS Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TCS Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/people.html">People</a>
        </div>
        <div class="menuitem"><a>product</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our PEOPLES</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Mr.G.Thiru</div>
                  <div class="itemprice">FOUNDER OF TCS</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Ian goodfellow</div>
                  <div class="itemprice">post:CEO</div>
              </div>
             
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">joo-hoo ley </div>
                  <div class="itemprice">Post:research director </div>
              </div>
            
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">jeremy howard fastai</div>
                  <div class="itemprice">Post: product designer</div>
              </div> 

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Ruslan salakhutdinov </div>
                  <div class="itemprice">Post: manufacturing specialist </div>
              </div>

               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/p6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Steven Sasson</div>
                  <div class="itemprice">Post: coordinator</div>
              </div>
              

          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 TCS Private Limited, Developed by Thiru.G
      </div>
    </div>
  </body>
</html>


CONTACT CODE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TCS Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">TCS Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/contact us.html">contact us</a>
        </div>
        <div class="menuitem"><a>product</a></div>
        <div class="menuitem"><a>people</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>TO CONTACT US</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/c1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Call us: </div>
                  <div class="itemprice">6381366409</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/c2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mail us:</div>
                  <div class="itemprice">eyespyindia@gmail.com</div>
              </div>
             
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="./img/c3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Reach us:</div>
                  <div class="itemprice">Block-87,Gandhi nagar,Chennai-81,Tamilnadu,India.</div>
              </div>
             

         </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 TCS Private Limited, Developed by Thiru.G.
      </div>
    </div>
  </body>
</html>

~~~


## OUTPUT:

![output1](./home.jpg)
![output2](./product.jpg)
![output3](./people.jpg)
![output4](./contact.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
