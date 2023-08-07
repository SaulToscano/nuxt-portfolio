<template>
  <section id="about">
    <div class="tile tile-1">
      <div>
        <h2>Front End</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>Tailwind</li>
          <li>JavaScript</li>
          <li>Typescript</li>
          <li>React</li>
          <li>Redux</li>
          <li>Next</li>
          <li>Remix</li>
          <li>Vue</li>
          <li>Nuxt</li>
        </ul>
        <img src="https://i.ibb.co/CMZDzKx/react.png" alt="" width="200" />
      </div>
    </div>
    <div class="tile tile-2">
      <div>
        <h2>ABOUT</h2>
        <p>
          <span>1 year front end programmer</span>
          <br/>
          <span>1 year back end programmer</span>
          </p>
          <br /><span>Frontend Experience:</span><br />
          <ul>
            <li>Eccomerce</li>
            <li>UI/UX</li>
            <li>Components</li>
            <li>Products implementations Shopify</li>
            <li>CDN Shopify</li>
          </ul>
          <br /><span>Backend Experience:</span><br />
          <ul>
            <li>sales report</li>
            <li>inventory reports</li>
            <li>scripts</li>
            <li>Shopify CDN</li>
            <li>paypal and stripe implementations</li>
          </ul>
        <img src="https://i.ibb.co/J2Zjvzw/45426762-1197435277078500-3313883099284111360-n.jpg" alt="" width="100" height="100" />
      </div>
    </div>
    <div class="tile tile-3">
      <div>
        <h2>Courses</h2>
        <ul style="font-size: 18px;">
          <li>2021 - 2022 Responsive web desing REALIZADO, FreeCode Camp</li>
          <li>2021 - 2022 HTML Course, Programing Hub</li>
          <li>2021 - 2022 JavaScript Course, Programing Hub</li>
          <li>2021 - 2022 Typescript Fundamentals Course, Platzi</li>
          <li>2021 - 2022 Advanced Types and Typescript Features, Platzi</li>
          <li>2021 - 2022 Object-oriented typescript and asynchronism, Platzi</li>
          <li>2021 - 2022 Vue Course: Introduction and Fundamentals, Platzi</li>
          <li>2021 - 2022 Vue Course: Reactivity in vue 3, Platzi</li>
          <li>2021 - 2022 Advanced React Course, Platzi</li>
          <li>2021 - 2022 Advanced React Hooks Course, Platzi</li>
          <li>2021 - 2022 React router 5 and Redux course, Platzi</li>
          <li>2021 - 2022 React.js and Redux Professional Course, Platzi</li>
        </ul>
        <img src="https://i.ibb.co/GHPsL8p/microsoft.png" alt="" width="300" />
      </div>
    </div>
    <div class="tile tile-4">
      <div>
        <h2>SERVICES</h2>
        <ul>
          <li>Git</li>
          <li>Jira / Confluence</li>
          <li>Docker</li>
          <li>Kubernetes</li>
          <li>Nginx</li>
          <li>AWS</li>
          <li>Heroku</li>
        </ul>
        <img src="https://i.ibb.co/6sFwpLz/cloud.png" alt="" width="300" />
      </div>
    </div>
    <div class="tile tile-5">
      <div>
        <h2>Back end</h2>
        <ul>
          <li>Express</li>
          <li>Sequelize</li>
          <li>Redis</li>
          <li>Bull</li>
          <li>Morgan</li>
          <li>Cypress</li>
          <li>Solid</li>
        </ul>
        <img src="https://i.ibb.co/0qZ462F/trophy.png" alt="" />
      </div>
    </div>
  </section>
</template>

<style>
li{
  margin: 10px 0;
}

#about {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 20px;
  padding: 20px;
}

#about .tile {
  border-radius: 10px;
  padding: 40px;
  box-sizing: border-box;
}

#about .tile-1 {
  background-color: #eee;
  grid-column: 1 / 2;
}

#about .tile-2 {
  background-color: #eee;
  grid-column: 2 / 3;
  grid-row: 1 / 3;
}

#about .tile-2 img {
  width: 400px;
  height: 400px;
  border-radius: 50%;
  object-fit: cover;
}

#about .tile-3 {
  background-color: #eee;
  grid-column: 3 / 4;
  grid-row: 1 / 2;
}

#about .tile-4 {
  background-color: #eee;
  grid-column: 1 / 2;
  grid-row: 2 / 3;
}

#about .tile-5 {
  background-color: #eee;
  grid-column: 3 / 4;
  grid-row: 2 / 3;
}

#about .tile {
  display: grid;
  align-items: center;
  justify-items: center;
  text-align: center;
  font-size: 1.5em;
}
</style>