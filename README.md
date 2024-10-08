<a name="readme-top"></a>
 
 
<!-- PROJECT LOGO -->
<br />
<div align="center">
   
  <a href="https://github.com/ibrsec/stockapp-frontend-selfservice">
    <img src="./public/logo.png" alt="Logo" width="250"   >
  </a>

  <h3 align="center">Stock App</h3>

  <p align="center">
    An awesome Stock App
    <!-- <a href="https://github.com/ibrsec/stockapp-frontend-selfservice"><strong>Explore the docs »</strong></a> -->
    <br />
    <br />
    <a href="https://stockapp-frontend-selfservice.vercel.app/">View Demo</a>
    ·
    <a href="https://backend-stockapi-express.vercel.app/documents/swagger/">Backend swagger</a>
    ·
    <a href="https://github.com/ibrsec/backend-stockapi">Backend repo</a>
    ·
    <a href="https://github.com/ibrsec/stockapp-frontend-selfservice/issues">Report Bug</a>
    ·
    <a href="https://github.com/ibrsec/stockapp-frontend-selfservice/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>📎 Table of Contents 📎 </summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
     <!-- <li><a href="#figma">Figma</a></li> -->
     <li><a href="#overview">Overview</a></li>
     <li><a href="#quick-setup">Quick Setup</a></li>
     <li><a href="#directory-structure">Directory structure</a></li>
     <li><a href="#built-with">Built With</a></li>
    <!-- <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li> -->

    
  </ol>
</details>





---

<!-- ABOUT THE PROJECT -->
<a name="about-the-project"></a>
## ℹ️ About The Project

[![stockapp-frontend-selfservice](./public/project.gif)](https://stockapp-frontend-selfservice.vercel.app/)




<p align="right">(<a href="#readme-top">back to top</a>)</p>


---

<!-- ## Figma 

<a href="https://www.figma.com/file/ePyCHKsx2ODB32uLgyUEEd/bootstrap-home-page?type=design&node-id=0%3A1&mode=design&t=edDzadCB9Ev5FS1a-1">Figma Link</a>  

  <p align="right">(<a href="#readme-top">back to top</a>)</p>




--- -->
<a name="overview"></a>
## 👀 Overview

📦 Frontend of the my [backend-stockapi](https://github.com/ibrsec/backend-stockapi) project </br></br>

🎯 <b>React Development:</b> Built a responsive frontend with React.js, delivering a seamless user experience.</br>

🛠 <b>State Management:</b> Utilized Redux Toolkit and Persist for consistent state management across sessions.</br>

🚀 <b>React Router:</b> Integrated React Router for smooth navigation between key sections like dashboard, products, and sales.</br>

📊 <b>UI Components:</b> Employed Material UI's DataGrid and Charts for interactive tables and data visualizations.</br>

📝 <b>Form Validation:</b> Managed forms with Formik and Yup for accurate data input and validation.</br>

🔔 <b>User Notifications:</b> Added real-time feedback using Toastify for actions like adding or editing records.</br>

💾 <b>CRUD Operations:</b> Implemented full CRUD functionality for products, sales, firms, and more.</br>

🃏 <b>Card Layouts:</b> Designed intuitive card-based interfaces for managing firms and brands.</br>

📊 <b>Data Tables:</b> Organized stock information in editable tables for easy data management.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<a name="quick-setup"></a>
## 🛫 Quick Setup

```sh
# clone the project
git clone https://github.com/ibrsec/stockapp-frontend-selfservice.git

# enter the project directory
cd stockapp-frontend-selfservice

# install dependency
npm install || yarn install

# develop
npm run dev || yarn start
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ## 🐞 Debug

![stockapp-frontend-selfservice.gif](/stockapp-frontend-selfservice.gif) -->








<a name="directory-structure"></a>
## 📂 Directory structure 

```diff
stockapp-frontend-selfservice  (folder)
  |          
  |---public (folder) 
  |                
+ |---src (folder) 
  |     |---assests (folder) 
  |     |           
  |     |---pages (folder)       
  |     |           
  |     |---components (folder) 
  |     |    
  |     |---app (folder)       
  |     |     └---store.jsx       
  |     |          
  |     |---features (folder)       
  |     |     |---authSlice.jsx  
  |     |     └---stockSlice.jsx       
  |     |          
  |     |---router (folder)        
  |     |     |---PrivateRoute.jsx  
  |     |     └---AppRouter.jsx       
  |     |          
  |     |---router (folder)        
  |     |     |---useAxios.jsx  
  |     |     |---useApiRequests.jsx  
  |     |     └---useStockRequest.jsx       
  |     |          
  |     |---helper (folder)        
  |     |     └---ToastNotify.js       
  |     |          
  |     |---App.js 
  |     |---Index.js
  |     └---Index.css
  |      
  |----package.json
  |----yarn.lock
  |----tailwind.config.js
  |----.env.local
  └----readme.md 
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<a name="built-with"></a>
### 🏗️ Built With

 
<!-- https://dev.to/envoy_/150-badges-for-github-pnk  search skills-->

 <img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white">
 <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white&color=red"> 
 <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
 <!-- <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white">  -->
 <!-- <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white">  -->
 <!-- <img src="https://img.shields.io/badge/Vite-AB4BFE?style=for-the-badge&logo=vite&logoColor=FFC920">  -->
 <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"> 
 <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white"> 

 <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white"> 
 <img src="https://img.shields.io/badge/Redux Toolkit-593D88?style=for-the-badge&logo=redux&logoColor=white"> 
 <img src="https://img.shields.io/badge/Redux--Persist -593D88?style=for-the-badge&logo=redux&logoColor=white"> 
 <!-- <img src="https://img.shields.io/badge/Context API-593D88?style=for-the-badge&logo=context&logoColor=white">  -->


 <img src="https://img.shields.io/badge/Axios-593D88?style=for-the-badge&logo=axios&logoColor=white"> 
 <!-- <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">  -->

 <img src="https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white"> 
 <img src="https://img.shields.io/badge/Formik-172B4D?style=for-the-badge&logo=formik&logoColor=white"> 
 <img src="https://img.shields.io/badge/Yup-172B4D?style=for-the-badge&logo=yup&logoColor=white"> 
 <img src="https://img.shields.io/badge/Toastify-45CC11?style=for-the-badge&logo=toastify-ui&logoColor=white"> 
 



 
<p align="right">(<a href="#readme-top">back to top</a>)</p>


