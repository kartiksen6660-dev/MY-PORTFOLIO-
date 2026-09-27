<!DOCTYPE html>
<html>
  <head>
    <title>Mera Portfolio</title>
    <style>
body {
  font-family: Arial;
  background-color: white;
}

h1 {
  color: white;
  background-color: purple;
  text-align: center;
  padding: 20px;
}

.purple-text {
  color: purple;
}

.green-text {
  color: green;
}

nav a {
  color: black;
  margin: 0 15px;
  text-decoration: none;
}

table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
  padding: 10px;
}

th {
  background-color: purple;
  color: white;
}

input,
textarea {
  width: 100%;
  padding: 10px;
  border-radius: 5px;
}

button {
  background-color: green;
  color: white;
  padding: 10px 20px;
  border: none;
}

button:hover {
  background-color: darkgreen;
}

footer {
  background-color: dimgray;
  color: white;
  text-align: center;
  padding: 15px;
}
    </style>
  </head>
  <body>
    <h1>MY NAME IS KARTIK. I PREPARE BCA SKILLS</h1>
    
    <section>
    <h2>About Me</h2>
    <p class="purple-text">
        Mera naam Kartik hai. Main ek student hoon aur web development seekh raha hoon.
    </p>
    <p class="green-text">
        Mera goal HTML, CSS aur JavaScript ko achchhe se seekhkar ek skilled web developer banna hai.
    </p>
    </section>
    
    <hr>
    
    <h2>MY SKILLS</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Web Development</li>
    </ul>
    
    <table border="1">
      <tr>
        <th>STEP</th>
        <th>SUBJECT</th>
      </tr>
      <tr>
        <td>1</td>
        <td>html</td>
      </tr>
      <tr>
        <td>2</td>
        <td>css</td>
      </tr>
      <tr>
        <td>3</td>
        <td>JavaScript</td>
      </tr>
      <tr>
        <td>4</td>
        <td>web developer</td>
      </tr>
    </table>
    
    <h2>CONTACT FORM</h2>
    <form>
      <label>NAME</label>
      <br>
      <input type="text">
      <br><br>
      <label>EMAIL</label>
      <br>
      <input type="email">
      <br><br>
      <label>MESSAGE</label>
      <br>
      <textarea rows="5"></textarea>
      <br><br>
      <button>submit</button>
    </form>
   <br> 
    <footer>
      MADE BY KARTIK SEN
    </footer>
  </body>
</html>
