<template>
  <section id="menu">
    <div class="tile about-tile">
      <a href="#about" id="boton">
        <div class="front"></div>
        <div class="back">ABOUT</div>
      </a>
    </div>
    <div class="tile projects-tile">
      <a href="#projects">
        <div class="front"></div>
        <div class="back">PROJECTS</div>
      </a>
    </div>
    <div class="tile posts-tile">
      <a href="#posts">
        <div class="front"></div>
        <div class="back">POSTS</div>
      </a>
    </div>
    <div class="tile contact-tile">
      <a href="#contact">
        <div class="front"></div>
        <div class="back">CONTACT</div>
      </a>
    </div>
  </section>
</template>

<style>
#menu {
  background-color: rgb(195, 35, 88);
  display: grid;
  grid-template-columns: repeat(4, 200px);
  grid-template-rows: repeat(2, 200px);
  justify-content: center;
  align-content: center;
  grid-template-areas:
    "about about projects projects"
    "about about posts contact";
}

#menu .tile {
  height: 100%;
  overflow: hidden;
  cursor: pointer;
}

#menu .tile a {
  text-decoration: none;
}

#menu .tile .front {
  color: white;
  background-color: black;
  height: 100%;
  display: grid;
  justify-items: center;
  align-items: center;
  transition: all 0.3s ease;

  padding: 20px;
  box-sizing: border-box;
}

#menu .tile:hover .front {
  margin-top: -100%;
}

#menu .projects-tile:hover .front {
  margin-top: -50%;
}

#menu .tile .back {
  background-color: #222;
  color: white;
  display: grid;
  justify-items: center;
  align-items: center;
  height: 100%;
  font-weight: bold;
  font-size: 28px;
}

#menu .logo-tile {
  grid-area: logo;
  background-color: red;
}

#menu .about-tile {
  grid-area: about;
  background-color: red;
}

#menu .about-tile .front {
  background-image: url('https://i.ibb.co/VwGSZsV/profile.png');
  background-size: cover;
  background-position: top center;
}

#menu .projects-tile {
  grid-area: projects;
  background-color: yellow;
}

#menu .projects-tile .front {
  background-image: url('https://i.ibb.co/87J69Q4/work-01.png');
  background-size: cover;
  background-position: top center;
}

#menu .posts-tile {
  grid-area: posts;
  background-color: rgb(0, 255, 119);
}

#menu .posts-tile .front {
  background-image: url('https://i.ibb.co/CV4RP7g/work-02.png');
  background-size: cover;
  background-position: top center;
}

#menu .contact-tile {
  grid-area: contact;
  background-color: rgb(255, 0, 208);
}

#menu .contact-tile .front {
  background-image: url('https://i.ibb.co/z6yqtCX/work-03.png');
  background-size: cover;
  background-position: top center;
}</style>