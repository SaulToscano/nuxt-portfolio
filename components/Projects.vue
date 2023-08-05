<template>
  <section id="projects">
    <div class="tile main-photo">
      <h2>POSTS</h2>

      <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste iusto
        soluta voluptate accusamus est praesentium at architecto nostrum
        inventore, a molestias eaque minus sequi magni distinctio fuga eveniet
        asperiores consequuntur.
      </div>
    </div>
    <div class="tile photo-2">
      <a href="#"></a>
    </div>
    <div class="tile photo-3">
      <a href="#"></a>
    </div>
    <div class="tile photo-4">
      <a href="#"></a>
    </div>
    <div class="tile photo-5">
      <a href="#"></a>
    </div>
    <div class="tile photo-17">
      <a href="#"></a>
    </div>
    <div class="tile photo-6">
      <a href="#"></a>
    </div>
    <div class="tile photo-7">
      <a href="#"></a>
    </div>
    <div class="tile photo-8">
      <a href="#"></a>
    </div>
    <div class="tile photo-9">
      <a href="#"></a>
    </div>
    <div class="tile photo-10">
      <a href="#"></a>
    </div>
    <div class="tile photo-11">
      <a href="#"></a>
    </div>
    <div class="tile photo-12">
      <a href="#"></a>
    </div>
    <div class="tile photo-13">
      <a href="#"></a>
    </div>
    <div class="tile photo-14">
      <a href="#"></a>
    </div>
    <div class="tile photo-15">
      <a href="#"></a>
    </div>
    <div class="tile photo-16">
      <a href="#"></a>
    </div>
  </section>
</template>

<style>
#projects {
  background-color: black;
  display: grid;
  grid-template-columns: repeat(10, 1fr);
  grid-template-rows: repeat(10, 1fr);
  gap: 10px;
  padding: 10px;
  grid-auto-flow: row;
  grid-template-areas:
    "main-photo main-photo main-photo photo-2 photo-2 photo-2 photo-3 photo-3 photo-4 photo-4"
    "main-photo main-photo main-photo photo-2 photo-2 photo-2 photo-3 photo-3 photo-4 photo-4"
    "main-photo main-photo main-photo photo-2 photo-2 photo-2 photo-5 photo-17 photo-4 photo-4"
    "main-photo main-photo main-photo photo-7 photo-7 photo-6 photo-6 photo-6 photo-4 photo-4"
    "main-photo main-photo main-photo photo-7 photo-7 photo-6 photo-6 photo-6 photo-9 photo-9"
    "main-photo main-photo main-photo photo-7 photo-7 photo-8 photo-8 photo-8 photo-8 photo-8"
    "main-photo main-photo main-photo photo-10 photo-10 photo-8 photo-8 photo-8 photo-8 photo-8"
    "main-photo main-photo main-photo photo-10 photo-10 photo-11 photo-11 photo-11 photo-12 photo-12"
    "main-photo main-photo main-photo photo-13 photo-14 photo-11 photo-11 photo-11 photo-12 photo-12"
    "main-photo main-photo main-photo photo-15 photo-16 photo-11 photo-11 photo-11 photo-12 photo-12";
}

#projects .tile {
  background-color: #ccc;
  border-radius: 5px;

  background-size: cover;
  background-position: center center;
}

#projects .tile:not(.main-photo) {
  opacity: 0.5;
  transition: all 0.1s ease-in;
}

#projects .tile:hover:not(.main-photo) {
  transform: scale(0.99);
  opacity: 1;
}

#projects .tile a {
  display: grid;
  height: 100%;
}

#projects .main-photo {
  background-color: red;
  grid-area: main-photo;
  padding: 20px;
  color: white;
  font-size: 20px;

  background-image: url('../assets/images/work-17.png');
}

#projects .main-photo h2,
#projects .main-photo div {
  background-color: black;
  display: inline-block;
  padding: 20px;
  border-radius: 5px;
}

#projects .photo-2 {
  background-color: yellow;
  background-image: url('../assets/images/work-01.png');

  grid-area: photo-2;
}

#projects .photo-3 {
  background-color: aqua;
  grid-area: photo-3;

  background-image: url('../assets/images/work-02.png');
}

#projects .photo-4 {
  background-color: chocolate;
  grid-area: photo-4;

  background-image: url('../assets/images/work-03.png');
}

#projects .photo-5 {
  background-color: cornflowerblue;
  grid-area: photo-5;

  background-image: url('../assets/images/work-04.png');
}

#projects .photo-17 {
  background-color: crimson;
  grid-area: photo-17;

  background-image: url('../assets/images/work-05.png');
}

#projects .photo-6 {
  background-color: darkcyan;
  grid-area: photo-6;

  background-image: url('../assets/images/work-06.png');
}

#projects .photo-7 {
  background-color: darkkhaki;
  grid-area: photo-7;

  background-image: url('../assets/images/work-07.png');
}

#projects .photo-8 {
  background-color: darkviolet;
  grid-area: photo-8;

  background-image: url('../assets/images/work-09.png');
}

#projects .photo-9 {
  background-color: deepskyblue;
  grid-area: photo-9;

  background-image: url('../assets/images/work-08.png');
}

#projects .photo-10 {
  background-color: green;
  grid-area: photo-10;

  background-image: url('../assets/images/work-10.png');
}

#projects .photo-11 {
  background-color: darkorange;
  grid-area: photo-11;

  background-image: url('../assets/images/work-11.png');
}

#projects .photo-12 {
  background-color: darkseagreen;
  grid-area: photo-12;

  background-image: url('../assets/images/work-12.png');
}

#projects .photo-13 {
  background-color: indianred;
  grid-area: photo-13;

  background-image: url('../assets/images/work-13.png');
}

#projects .photo-14 {
  background-color: indigo;
  grid-area: photo-14;

  background-image: url('../assets/images/work-14.png');
}

#projects .photo-15 {
  background-color: lightblue;
  grid-area: photo-15;

  background-image: url('../assets/images/work-15.png');
}

#projects .photo-16 {
  grid-area: photo-16;

  background-image: url('../assets/images/work-16.png');
}
</style>