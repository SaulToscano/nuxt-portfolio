<template>
  <section id="contact">
    <form action="">
      <h2>CONTACT ME</h2>
      <label for="name">Name</label>
      <input type="text" />

      <label for="name">Subject</label>
      <input type="text" />

      <label for="name">Content</label>
      <textarea name="" id="" cols="30" rows="10"></textarea>

      <input type="submit" value="Enviar" />
    </form>
    <div class="social-networks">
      <a href="">Twitter</a>
      <a href="">Facebook</a>
      <a href="">Instagram</a>
    </div>
  </section>
</template>

<style>
#contact {
  background-color: rgb(26, 72, 151);
  display: grid;
  grid-template: auto 100px / 700px;
  justify-content: center;
  align-content: center;
  box-sizing: border-box;
}

#contact form {
  padding: 20px;
  color: white;
  display: grid;
  gap: 15px;
  grid-template: auto / auto;
  align-items: center;
  box-sizing: border-box;
}

#contact form input,
#contact form textarea {
  padding: 20px 10px;
  box-sizing: border-box;
  font-size: 18px;
  border-radius: 5px;
  border: none;
  width: 100%;
}

#contact .social-networks {
  justify-self: center;
  padding: 10px 0;
}

#contact form input[type="submit"] {
  background-color: #67ca50;
  font-weight: bold;
  font-size: 28px;
}

#contact .social-networks a {
  color: white;
}
</style>