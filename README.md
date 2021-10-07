


[![LinkedIn][linkedin-shield]][linkedin-url]




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/eliac7/portfolio-in-react">
    <img src="https://iliasdev.eu/share.jpg" width="500">
  </a>

<h3 align="center">My Portfolio</h3>

  <p align="center">
My portfolio was designed and implemented by me. You can visit the live version <a href="https://iliasdev.eu">here</a>.
    <br />
    <br />
    <br />
    ·
    <a href="https://github.com/eliac7/portfolio-in-react/issues">Report Bug</a>
    ·
    <a href="https://github.com/eliac7/portfolio-in-react/issues">Request Feature</a>
  </p>
</div>




<!-- ABOUT THE PROJECT -->
## About The Project

I made my portfolio to show on what projects I have already worked on and get my hands dirty on React.js concept. There is the front-end and the back-end. For the front-end part, I used React.js with React-Bootstrap and axios to get my projects through the Rest API I made. Also, I used Firebase storage to save my screenshots of my projects and EmailJS to make the contact form. Additionally, I used yup resolver to validate any fields, AOS for animating elements, Styled-Components, data React Data Table Component for showing users and finally UUID to generate an ID before pushing image to Firebase storage. 

For the back-end, I used Node.js with Express and MongoDB for the database. You can check the API Repo [here](https://github.com/eliac7/projects-rest-api).

Except the main homepage, there is an Admin dashboard which can make CRUD (Create,Remove,Update,Delete) operations for my projects and users.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [React.js](https://reactjs.org/)
* [React Bootstrap](https://react-bootstrap.github.io/)
* [Firebase](https://firebase.google.com/)
* [Node.js](https://nodejs.org/en/)
* [Expressjs](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)



<p align="right">(<a href="#top">back to top</a>)</p>


<!-- SCREENSHOT EXAMPLES -->
## Screenshots
![image](https://i.imgur.com/zaQ1nLW.png)

<div align="center">
  <i>Main admin panel</i>
</div>

![image](https://user-images.githubusercontent.com/26083840/136392835-66b5ae14-cb49-467c-94f0-370e802dbbf4.png)

<div align="center">
  <i>All skills</i>
</div>

![image](https://i.imgur.com/ItV6Cf6.jpg)

<div align="center">
  <i>Users datatable</i>
</div>




<p align="right">(<a href="#top">back to top</a>)</p>




<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

You will need npm and yarn.
* npm
  ```sh
  npm install npm@latest -g
  ```
* yarn
  ```sh
  npm install --global yarn
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/eliac7/portfolio-in-react.git
   ```
2. Install Yarn packages
   ```sh
   yarn install
   ```
3. Enter API tokens in `.env`
   ```
   REACT_APP_USER_ID = FROM_EMAILJS
    REACT_APP_TEMPLATE_ID = FROM_EMAILJS
    REACT_APP_API_TOKEN = 19978812345678910
    REACT_APP_FIREBASE_API_KEY = GET_IT_FROM_FIREBASE
    REACT_APP_FIREBASE_AUTH_DOMAIN = GET_IT_FROM_FIREBASE
    REACT_APP_FIREBASE_PROJECT_ID = GET_IT_FROM_FIREBASE
    REACT_APP_FIREBASE_STORAGE_BUCKET = GET_IT_FROM_FIREBASE
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID = GET_IT_FROM_FIREBASE
    REACT_APP_FIREBASE_APP_ID = GET_IT_FROM_FIREBASE
    REACT_APP_FIREBASE_MEASUREMENT_ID = GET_IT_FROM_FIREBASE
    REACT_APP_RECAPTCHA_SITE_KEY = GET_IT_FROM_GOOGLE_RECAPTCHA
    REACT_APP_RECAPTCHA_SECRET_KEY = GET_IT_FROM_GOOGLE_RECAPTCHA
   ```

<p align="right">(<a href="#top">back to top</a>)</p>





<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Ilias Thalassochoritis - [@ilias_thal](https://twitter.com/ilias_thal) - elias_thal[at]hotmail.com

Project Link: [https://github.com/eliac7/portfolio-in-ract](https://github.com/eliac7/portfolio-in-ract)

<p align="right">(<a href="#top">back to top</a>)</p>






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/eliac7/
[product-screenshot]: images/screenshot.png
