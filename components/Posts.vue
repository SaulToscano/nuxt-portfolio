<template>
  <section id="posts">
    <div class="post post-1">
      <a href="#">
        <div class="title">
          <h3>La ciencia detras del arte</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
            iure nesciunt atque nam illo dolore ipsa asperiores cumque
          </p>
        </div>
      </a>
    </div>
    <div class="post post-2">
      <a href="#">
        <div class="title">
          <h3>La ciencia detras del arte</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
            iure nesciunt atque nam illo dolore ipsa asperiores cumque
          </p>
        </div>
      </a>
    </div>
    <div class="post post-3">
      <a href="#">
        <div class="title">
          <h3>La ciencia detras del arte</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
            iure nesciunt atque nam illo dolore ipsa asperiores cumque
          </p>
        </div>
      </a>
    </div>
    <div class="post post-4">
      <a href="#">
        <div class="title">
          <h3>La ciencia detras del arte</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
            iure nesciunt atque nam illo dolore ipsa asperiores cumque
          </p>
        </div>
      </a>
    </div>
    <div class="post post-5">
      <a href="#">
        <div class="title">
          <h3>La ciencia detras del arte</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
            iure nesciunt atque nam illo dolore ipsa asperiores cumque
          </p>
        </div>
      </a>
    </div>
    <div class="post post-6">
      <a href="#">
        <div class="title">
          <h3>La ciencia detras del arte</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
            iure nesciunt atque nam illo dolore ipsa asperiores cumque
          </p>
        </div>
      </a>
    </div>
  </section>
</template>

<style>
#posts {
  padding: 10px;
  background-color: rgb(66, 186, 255);
  display: grid;
  grid-template: repeat(2, 300px) / repeat(3, 350px);
  gap: 10px;
  justify-content: center;
  align-content: center;
}

#posts .post {
  display: grid;
  align-content: end;
  border-radius: 5px;
  background-color: white;

  background-size: cover;
  background-position: center center;

  overflow: hidden;
}

#posts .post a {
  color: white;
  text-decoration: none;
}

#posts .post .title {
  background-color: rgba(0, 0, 0, 0.7);
  color: white;
  padding: 10px;
}

#posts .post .title:hover {
  background-color: white;
  color: black;
}

#posts .post.post-1 {
  background-image: url('https://i.ibb.co/CPGRV90/work-15.png');
}

#posts .post.post-2 {
  background-image: url('https://i.ibb.co/CV4RP7g/work-02.png');
}

#posts .post.post-3 {
  background-image: url('https://i.ibb.co/gWxCKWz/work-05.png');
}

#posts .post.post-4 {
  background-image: url('https://i.ibb.co/jTJs0Pr/work-08.png');
}

#posts .post.post-5 {
  background-image: url('https://i.ibb.co/SVpwDYc/work-10.png');
}

#posts .post.post-6 {
  background-image: url('https://i.ibb.co/CPGRV90/work-15.png');
}</style>