# mama_recipe_app
<div align="center"><img src="https://github.com/ainurcoding/blanja_app_fe/blob/master/src/assets/images/blanja_icon.png" height="50" width="50"/></div>
<div align='center'><a href='https://github.com/ainurcoding/blanja_app_api'> >>Visit backend repository<< </a></div>
<hr />

### Description

<p>Blanja App is a Business to Customer  e-commerce application that makes transactions between website services and online sellers, where online sellers can post their wares on this website. This website is built with PERN technology (PSQL, ExpressJS, ReactJS, and NodeJS). This website is built on teamwork, and I act as a front-end developer, where the front-end developer is in charge of making this website more dynamic with the API provided by the back-end team. ReactJS is the technology that I use in developing the front end for this website.


</p>
<hr/>

## General Information

### Table of contents

<div id='table-of-content'>List</div>

- <a href='#build-with'>Build With</a>
- <a href='#structure-folder'>Structure Folder</a>
- <a href='#installation-guide'>Installation Guide</a>
- <a href='#commands'>Commands</a>
- <a href='#endpoint'>Endpoint Application</a>
- <a href='#ss-app'>Screenshot Application</a>
- <a href='#packages-included'>Packages Included</a>
- <a href='#demo-application'>Demo Application</a>
- <a href='#for-more-information'>For More Information</a>



### Build with 
<ul id='build-with'>
  <li><a href='https://html5.org/'>HTML 5: for markup language</a></li>
  <li><a href='https://www.w3.org/Style/CSS/Overview.en.html'>CSS: for styling website display</a></li>
  <li><a href='https://nodejs.org/en/'>NodeJS: for main language set dynamic website application</a></li>
  <li><a href='https://reactjs.org/'>React JS: for library from node to create powerfull website application</a></li>
  <li><a href='https://html5.org/'>Bootstrap: a library framework of CSS/HTML/JS </a></li>
  <li><a href='https://html5.org/'>Axios: dependency for fetching data from API</a></li>
  <li><a href='https://github.com/ainurcoding/mama_recipe_app/blob/master/frontend/package.json'>and se more for dependecy on package.json</a></li>
</ul>

<a href='#table-of-content'>Back to top</a>
<hr />

### Structure Folder 

<p id='structure-folder'>Frontend</p>
<ul>
  <li>public || <span><b><i>You can drop anything if that is accesseble for public</i></b></span></li>
  <li>src</li>
  <ul>
    <li>assets ||<span><b><i>You can store various needs for this website, such as images, styles, javascript, and others.</i></b></span></li>
    <li>components ||<span><b><i>This folder is for storing layouts, such as Navbar.</i></b></span></li>
    <li>pages ||<span><b><i>This folder is the main folder in the website display for this application.</i></b></span></li>
    <li>redux ||<span><b><i>Redux to set the global state, as well as the use of user data.</i></b></span></li>
    <li>router ||<span><b><i>The router is used to set the endpoint of this application.</i></b></span></li>
  </ul>
</ul>
<a href='#table-of-content'>Back to top</a>
<hr/>

### Installation Guide 
<p id='installation-guide'>Frontend</p>
<ol type="1">
  <li>Make sure your backend is ready to use, and the backend server is running.</li>
  <li>Set .env in the frontend folder to be your backend URL for example, your backend server is: <b>'localhost:5000'</b>.</li>
  <li>Run the front-end server with the command npm run start on Shell / Git Bash.</li>
  <li>To run the server that has been set, use the <b>npm run dev command</b>.</li>
  <li>If the website page has appeared, then the front end is ready to use.</li>
</ol>

<a href='#table-of-content'>Back to top</a>
<hr />

### Commands 
<p id='commands'>Running the Application</p>

`npm run start`

Build the Application

`npm run build`

Testing the Application

`npm run test`

Eject The Application

`npm run eject`

<a href='#table-of-content'>Back to top</a>
<hr />

### Endpoint of Application 

<p id='endpoint'>List</p>

- user
`PATH /` - Access Landing page\
`PATH /login` - Access Login page\
`PATH /register` - Access Register page\
`PATH /resetpass` - Access Reset password page\
`PATH /product/:id_product` - Access product page\
`PATH /checkout` - Access checkout page\
`PATH /profile` - Access profile page\
`PATH /mybag` - Access mybag page\
`PATH /category` - Access category page\
`PATH /chat` - Access chat page\
`PATH /edit-product/:id` - Access edit product page
- admin
`PATH /admin/` - Access login admin page\
`PATH /admin/home` - Access home admin page\
`PATH /admin/order` - Access order admin page\
`PATH /admin/product` - Access product admin page\

<a href='#table-of-content'>Back to top</a>
<hr />

### Screenshot Application 

<details id='ss-app' >
  <summary>
    Login Page
  </summary>
<img src="https://github.com/ainurcoding/blanja_app_fe/blob/master/screenshot/login.png" alt="login page" />
</details>

<details>
  <summary>
    Register Page
  </summary>
<img src="https://github.com/ainurcoding/blanja_app_fe/blob/master/screenshot/register.png" alt="register page" />
</details>

<details>
  <summary>
    Forgot Password Page
  </summary>
<img src="./screenshot/forgot_pass.png" alt="forgot password page" />
</details>

<details>
  <summary>
    Reset Password Page
  </summary>
<img src="./screenshot/reset_pass.png" alt="reset password page" />
</details>

<details>
  <summary>
    Landing Page
  </summary>
<img src="./screenshot/landing.png" alt="landing page" />
</details>

<details>
  <summary>
    Search Product Page
  </summary>
<img src="./screenshot/search_product.png" alt="search product page" />
</details>

<details>
  <summary>
    Product Detail Page
  </summary>
<img src="./screenshot/product_detail.png" alt="product detail page" />
</details>

<details>
  <summary>
    Chat Page
  </summary>
<img src="./screenshot/chat.png" alt="chat page" />
</details>

<details>
  <summary>
    MyBag Page
  </summary>
<img src="./screenshot/mybag.png" alt="mybag page" />
</details>

<details>
  <summary>
    Checkout Page
  </summary>
<img src="./screenshot/checkout.png" alt="checkout page" />
</details>

<details>
  <summary>
    Customer Profile
  </summary>
<img src="./screenshot/profil_customer.png" alt="customer profile" />
</details>

<details>
  <summary>
    Customer Address
  </summary>
<img src="./screenshot/customer_address.png" alt="customer address" />
</details>

<details>
  <summary>
    Customer MyOrder
  </summary>
<img src="./screenshot/myorder.png" alt="myorder" />
</details>

<details>
  <summary>
    Seller Profile
  </summary>
<img src="./screenshot/seller_profile.png" alt="seller profile" />
</details>

<details>
  <summary>
    Seller MyProduct
  </summary>
<img src="./screenshot/myproduct.png" alt="myproduct" />
</details>

<details>
  <summary>
    Seller Edit Product
  </summary>
<img src="./screenshot/update_product.png" alt="update product" />
</details>

<details>
  <summary>
    Seller Insert Product
  </summary>
<img src="./screenshot/seller_insert_product.png" alt="insert product" />
</details>

<details>
  <summary>
    Seller Orders
  </summary>
<img src="./screenshot/seller_order.png" alt="seller order" />
</details>

<details>
  <summary>
    Admin Login
  </summary>
<img src="./screenshot/admin/admin_login.png" alt="admin login" />
</details>

<details>
  <summary>
    Admin Landing
  </summary>
<img src="./screenshot/admin/admin_landing.png" alt="admin landing" />
</details>

<details>
  <summary>
    Admin List Order
  </summary>
<img src="./screenshot/admin/admin_order_list.png" alt="admin list order" />
</details>

<details>
  <summary>
    Admin List Product
  </summary>
<img src="./screenshot/admin/admin_product_list.png" alt="admin list product" />
</details>

<a href='#table-of-content'>Back to top</a>
<hr />

### Packages Included 

- <p id='packages-included'>NPM dependencies</p>


  ![](https://img.shields.io/badge/bcrypt-v5.0.1-blue)
  ![](https://img.shields.io/badge/body--parser-v1.19.2-blue)
  ![](https://img.shields.io/badge/cors-v2.8.5-blue)
  ![](https://img.shields.io/badge/dotenv-v16.0.0-blue)
  ![](https://img.shields.io/badge/express-v4.17.3-blue)
  ![](https://img.shields.io/badge/express--validator-v5.3.1-blue)
  ![](https://img.shields.io/badge/helmet-v5.0.2-blue)
  ![](https://img.shields.io/badge/pg-v8.7.3-blue)
  ![](https://img.shields.io/badge/multer-v1.4.4-blue)
  ![](https://img.shields.io/badge/xss--clean-v0.1.1-blue)
  ![](https://img.shields.io/badge/jsonwebtoken-v8.5.1-blue)
  ![](https://img.shields.io/badge/sweetalert-v2.1.2-blue)
  ![](https://img.shields.io/badge/reactstrap-v9.0.2-blue)
  ![](https://img.shields.io/badge/react-router-dom-v6.3.0-blue)
  ![](https://img.shields.io/badge/react-dom-v17.0.2-blue)
  ![](https://img.shields.io/badge/react-v17.0.2-blue)
  ![](https://img.shields.io/badge/jwt-decode-v3.1.2-blue)
  ![](https://img.shields.io/badge/axios-v0.26.1-blue)
  ![](https://img.shields.io/badge/bootstrap-v5.1.3-blue)
  
<a href='#table-of-contents'>Back to top</a>
<hr />

### Demo Application
<p id='demo-application'><a href='https://github.com/ainurcoding/blanja_app_api'>Visit backend repository</a></p>
<p>Visit this link for app demo <a href='https://blanja-app-fe.vercel.app/'>Blanja App</a></p>

<a href='#table-of-content'>Back to top</a>
<hr />

### For More Information 
<p id='for-more-information'>My Social media account:</p> <br />
<div>
<img height="25" width="25" src='https://camo.githubusercontent.com/c9dacf0f25a1489fdbc6c0d2b41cda58b77fa210a13a886d6f99e027adfbd358/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f696e7374616772616d2e737667' alt='ig-icon'></img><span> : @ainurridwan_</span>
</div>

<div>
<img height="25" width="25" src='https://camo.githubusercontent.com/4a3dd8d10a27c272fd04b2ce8ed1a130606f95ea6a76b5e19ce8b642faa18c27/68747470733a2f2f6564656e742e6769746875622e696f2f537570657254696e7949636f6e732f696d616765732f7376672f676d61696c2e737667' alt='gmail-icon'></img><span> : ainurridwank2@gmail.com</span>
</div>

<a href='#table-of-content'>Back to top</a>

<div align='center'>
:copyright: Ainur Ridwan, 2022
</div>

