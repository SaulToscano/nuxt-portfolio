<template>
  <section id="about">
    <div class="tile tile-1">
      <div>
        <h2>STACK</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus
          tempore accusantium voluptates corrupti facere culpa necessitatibus,
        </p>
        <img src="../public/react.png" alt="" width="200" />
      </div>
    </div>
    <div class="tile tile-2">
      <div>
        <h2>ABOUT</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus
          tempore accusantium voluptates corrupti facere culpa necessitatibus,
        </p>
        <!-- <img src="img/profile.png" alt="" width="100" height="100" /> -->
      </div>
    </div>
    <div class="tile tile-3">
      <div>
        <h2>REFERENCES</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus
          tempore accusantium voluptates corrupti facere culpa necessitatibus,
        </p>
        <!-- <img src="img/microsoft.png" alt="" width="300" /> -->
      </div>
    </div>
    <div class="tile tile-4">
      <div>
        <h2>SERVICES</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus
          tempore accusantium voluptates corrupti facere culpa necessitatibus,
        </p>
        <!-- <img src="img/cloud.png" alt="" width="300" /> -->
      </div>
    </div>
    <div class="tile tile-5">
      <div>
        <h2>AWARDS</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus
          tempore accusantium voluptates corrupti facere culpa necessitatibus,
          nihil rem sequi deleniti quod repudiandae ratione nemo veniam sint,
          dignissimos a repellendus nisi.
        </p>
        <!-- <img src="img/trophy.png" alt="" /> -->
      </div>
    </div>
  </section>
</template>

<style>
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