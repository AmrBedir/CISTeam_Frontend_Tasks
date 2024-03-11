### HTML FORM
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <form action="#" style="width: 55%; height: 50%;" id="newForm" target="_blank" method="post">
      <fieldset>
        <legend>Registration Form</legend>
        <div class="input">
          <div class="user">
            <label for="name">UserName</label>
            <input type="text" name="" id="name">
          </div>
          <div class="password">
            <label for="pass">Password</label>
            <input type="password" name="" id="pass">
          </div>
        </div>
        <div class="gender">
          <label for="gender">Gender:</label>
          <br>
          <input type="radio" name="gender" id="gender" value="Male">Male <br>
          <input type="radio" name="gender" id="gender" value="Female">Female <br>
        </div>
        <br>
        <div style="margin-left: 20px;">
          <label for="cheklist">Choose Your Courses:</label>
          <br>
          <input type="checkbox" name="courses" id="cheklist" value="ITEM01">ITEM01 <input type="checkbox" name="courses" id="cheklist" value="ITEM02" style="margin-left: 55px;">ITEM02 <br>
          <input type="checkbox" name="courses" id="cheklist" value="ITEM03">ITEM03 <input type="checkbox" name="courses" id="cheklist" value="ITEM04" style="margin-left: 20px;">ITEM04
        </div>
        <br>
        <input type="submit" style="margin-left: 20px;" value="Submit">
        <input onclick="myfunction" type="reset" value="Reset">
    </form>
    <script>
      function myfunction() {
        document.getElementById("newForm").reset();
      }
    </script>
  </body>
</html>
```

```css
.input {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: flex-start;
  margin: 20px;
  margin-top: 40px;
}

.input input {
  width: 350px;
}

.input label {
  padding-right: 10px;
}

.pass {
  padding: 10px 0;
}

.pass label {
  margin-right: 10px;
}

.gender {
  margin-left: 20px;
}
```

### HTML TABLE
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    <table border="1" width="70%">
      <caption style="border: 4px double gray; font-weight: bold;">Time Table</caption>
      <tr>
        <th rowspan="6">Hours</th>
        <th>Mon</th>
        <th>Tue</th>
        <th>Wed</th>
        <th>Thu</th>
        <th>Fri</th>
      </tr>
      <tr>
        <td>Science</td>
        <td>Math</td>
        <td>Science</td>
        <td>Math</td>
        <td>Arts</td>
      </tr>
      <tr>
        <td>Science</td>
        <td>Math</td>
        <td>Science</td>
        <td>Math</td>
        <td>Arts</td>
      </tr>
      <tr>
        <th colspan="5">LUNCH</th>
      </tr>
      <tr>
        <td>Science</td>
        <td>Math</td>
        <td>Science</td>
        <td>Math</td>
        <td rowspan="2">Projects</td>
      </tr>
      <tr>
        <td>Science</td>
        <td>Math</td>
        <td>Science</td>
        <td>Math</td>
      </tr>
    </table>
  </body>
</html>
```
