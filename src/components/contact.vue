<template>
   <div class="container">
  <div class="contact">
    <h1>Contact Us</h1>
    <form>
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required>
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" required></textarea>
      </div>
      <button type="submit">Send Message</button>
    </form>
  </div>
</div>
  </template>
  
  <script>
  export default {
    name: 'contact',
    data () {
      return {
        title: 'Contact'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.contact {
  background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ6DttEMFO-zf_QEXnDayYgdgmwfGP6izdFmQ&usqp=CAU");
  border-radius: 5px;
  padding: 30px;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
  color: darkblue;
  font-weight: bold;
}

.contact h1 {
  font-size: 36px;
  margin-bottom: 20px;
  text-align: center;
  color: black;
}

.form-group {
  margin-bottom: 20px;
}

.form-group label {
  display: block;
  font-size: 18px;
  margin-bottom: 5px;
}

.form-group input,
.form-group textarea {
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 10px;
  font-size: 16px;
  width: 100%;
}

.form-group textarea {
  resize: none;
}

button[type="submit"] {
  background-color: #4CAF50;
  color: black;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;
}

button[type="submit"]:hover {
  background-color: #3e8e41;
}
  </style>
  