# Web Design for a Software Product Company

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
```
home.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tata Private Limited</title>
    
    
    <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/1.jpg" type="image/x-icon">
  </head>

  <body>
    <div class="container">
      <div class="banner">Tata Private Limited.</div>
      
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/proo1.png" alt="tech">
          <div class="contenttext">
            At Tata, we understand the importance of technology in enhancing business efficiency and empowering <br>
            entrepreneurs. That's why we design our products to be user-friendly and adaptable to your specific needs.<br><br>
            Our latest offering, Tata Prime, takes this to the next level by making the <br>
            transition to automation and our platform simpler than ever before.<br>
            With an intuitive interface and customizable features, you can easily discover the <br>
            full potential of the product without needing to learn any new skills.<br>
            Edusoft Prime adapts to your unique business and working style,<br>
            providing greater flexibility and a transformed look and feel<br>
            that will make you love it even more.<br>


            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Tata Private Limited, Developed by Sandhya Balamurali.
      </div>
    </div>
  </body>
</html>
product.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tata Private Limited</title>
     <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">
    
  </head>

  <body>
    <div class="container">
      <div class="banner"> Tata Private Limited.</div>
      <div class="menu">
     <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book1.jpg" alt="product image">
                  </div>
                  <div class="itemname"> Learning how to fly</div>
                  <div class="itemprice">Price: Rs.350 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The power of subconsious mind</div>
                  <div class="itemprice">Price: Rs.950 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book3.jpg" alt="product image">
                  </div>
                  <div class="itemname">The science of getting rich</div>
                  <div class="itemprice">Price: Rs.750 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book4.jpg" alt="product image">
                  </div>
                  <div class="itemname">Atomic Habits</div>
                  <div class="itemprice">Price: Rs.690 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book5.webp" alt="product image">
                  </div>
                  <div class="itemname">IKIGAI</div>
                  <div class="itemprice">Price: Rs.550 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book6.jpg" alt="product image">
                  </div>
                  <div class="itemname">The Alchemist</div>
                  <div class="itemprice">Price: Rs.450 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book7.jpg" alt="product image">
                  </div>
                  <div class="itemname">The Monk who sold his Ferrari</div>
                  <div class="itemprice">Price: Rs.2000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book8.jpg" alt="product image">
                  </div>
                  <div class="itemname">Think and Grow Rich</div>
                  <div class="itemprice">Price: Rs.700 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book9.jpg" alt="product image">
                  </div>
                  <div class="itemname">The Elements of Style</div>
                  <div class="itemprice">Price: Rs.400 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book10.webp" alt="product image">
                  </div>
                  <div class="itemname">Attitude is Everything</div>
                  <div class="itemprice">Price: Rs.600 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book11.jpg" alt="product image">
                  </div>
                  <div class="itemname">DO IT TODAY</div>
                  <div class="itemprice">Price: Rs.450 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/book12.webp" alt="product image">
                  </div>
                  <div class="itemname">Psychology of Money</div>
                  <div class="itemprice">Price: Rs.370 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Tata Private Limited, Sandhya Balamurali.
      </div>
    </div>
  </body>
</html>
people.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tata Private Limited</title>
    
     <link rel="stylesheet" href="/static/images/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">
    
  </head>

  <body>
    <div class="container">
      <div class="banner">Tata Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>PEOPLE AT TATA</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/people1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Sandhya Balamurali</div>
                  <div class="itemprice">President & CEO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/people2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Narthika Sundarapandian</div>
                  <div class="itemprice">Executive Vice President Operations</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/people3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Sabari Sathyanarayanan</div>
                  <div class="itemprice">Executive Vice President, Business Development & Marketing</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/people4.jpg" alt="product image">
                  </div>
                  <div class="itemname">Praisey Solomen</div>
                  <div class="itemprice">Executive Vice President Product Management and Development</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/people5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Nithyaasri Saravanan</div>
                  <div class="itemprice">Vice President, Finance & CFO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/people6.jpg" alt="product image">
                  </div>
                  <div class="itemname">Bindhya Balamurali</div>
                  <div class="itemprice">ETS Associate Vice President of Global TOEIC Management</div>
              </div>
             
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Tata Private Limited, Developed by Sandhya Balamurali
      </div>
    </div>
  </body>
</html>
contactus.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tata Private Limited</title>
   <link rel="stylesheet" href="/static/layout.css">
    <link rel="icon" href="/static/1.jpg" type="image/x-icon">
     
  </head>

  <body>
    <div class="container">
      <div class="banner">Tata Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
  <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
  <ul>
    <li>Address: 231, West Main Street, Delhi, India</li>
    <li>Phone: +91 8697027682</li>
    <li>Email: contact@tata.com</li></ul>
  
<h2> Sales Inquiries</h2>

<ul><li>India 1800 103 11231800 572 3535</li></ul>
    <h2>Press Inquiries</h2> 
<ul><li>press@tata.com</li>

<li>Nanya Sri</li>
<li>nanya@tata.com</li></ul>
    <h2>Analyst Relations</h2> 

    <ul><li>ragul</li>
    <li>+1-925-924-9500</li>
    <li>pr@tata.com</li></ul>
        <h2>Customer Relations</h2> 

    <ul><li>peter s.Balaji</li>
    <li>Director of Sales & Customer Service</li>
    <li>peterbalaji@tata.com</li>
    </ul>
    
  </div>
   <div class="footer">
        Copyright &#169; 2021 Tata Private Limited, Developed by Sandhya Balamurali.
      </div>
      </div>
</body>
</html>
```
## OUTPUT:
![home](https://user-images.githubusercontent.com/115525118/215143138-22ae1c49-7c40-4525-93a4-e7d92ee62c92.png)
![people](https://user-images.githubusercontent.com/115525118/215143164-130ec4e5-b1b3-41ae-a208-f61d45017d45.png)
![contactus](https://user-images.githubusercontent.com/115525118/215143242-0094cf41-66bc-4a30-8fa3-a8cf4edea5a1.png)
![products](https://user-images.githubusercontent.com/115525118/215143198-136576b7-47d7-4b4b-a5d1-38925c6f99c3.png)
### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
