<!DOCTYPE html>
<html>
<head>
  <title>HTML टैग उदाहरण</title> <!-- (3) -->
  <meta charset="UTF-8"> <!-- (30) -->
  <link rel="stylesheet" href="styles.css"> <!-- (29) -->
</head>
<body> <!-- (4) -->

  <h1>यह H1 हेडिंग है</h1> <!-- (5) -->
  <h2>यह H2 हेडिंग है</h2>
  <h3>यह H3 हेडिंग है</h3>

  <p>यह एक पैराग्राफ है।</p> <!-- (6) -->

  <a href="https://www.google.com">गूगल पर जाएं</a> <!-- (7) -->

  <img src="image.jpg" alt="एक चित्र"> <!-- (8) -->

  <br> <!-- (9) -->
  <hr> <!-- (10) -->

  <div style="background-color: green;">यह एक डिव टैग है</div> <!-- (11) -->
  <span style="color: red;">यह एक स्पैन टैग है</span> <!-- (12) -->

  <ul> <!-- (13) -->
    <li>अनऑर्डर्ड लिस्ट आइटम</li> <!-- (15) -->
  </ul>

  <ol> <!-- (14) -->
    <li>ऑर्डर्ड लिस्ट आइटम</li>
  </ol>

  <table border="1"> <!-- (16) -->
    <tr> <!-- (17) -->
      <th>नाम</th> <!-- (19) -->
      <th>उम्र</th>
    </tr>
    <tr>
      <td>राम</td> <!-- (18) -->
      <td>25</td>
    </tr>
  </table>

  <form action="/submit"> <!-- (20) -->
    <label for="name">नाम:</label> <!-- (24) -->
    <input type="text" id="name" name="name"> <!-- (21) -->
    <br>
    <label for="message">संदेश:</label>
    <textarea id="message" name="message"></textarea> <!-- (22) -->
    <br>
    <label for="country">देश:</label>
    <select id="country" name="country"> <!-- (25) -->
      <option value="india">भारत</option> <!-- (26) -->
      <option value="usa">अमेरिका</option>
    </select>
    <br>
    <button type="submit">भेजें</button> <!-- (23) -->
  </form>

  <iframe src="https://example.com" width="300" height="200"></iframe> <!-- (27) -->

  <script> <!-- (28) -->
    console.log("Hello World!");
  </script>




</body>
</html>
