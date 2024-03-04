### Q1
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    <table width="100%" border="1">
      <caption>Members Data</caption>
      <tr>
        <th>Group</th>
        <th>Avatar</th>
        <th>Name</th>
        <th>Email</th>
        <th>Character</th>
        <th>Profile</th>
      </tr>
      <tr>
        <td rowspan="2">ninja</td>
        <td>
          <img decoding="async" src="https://via.placeholder.com/40/yellow" alt="">
        </td>
        <td>Osama <br>Mohamed </td>
        <td>o1@nn.sa
          <hr>o2@nn.sa
        </td>
        <td>&copy;</td>
        <td>
          <a href="profile.com">Profile</a>
        </td>
      </tr>
      <tr>
        <td>
          <img decoding="async" src="https://via.placeholder.com/40/red" alt="">
        </td>
        <td>Shady <br> Nabil </td>
        <td>s@nn.sa</td>
        <td>&trade;</td>
        <td>
          <a href="profile.com">Profile</a>
        </td>
      </tr>
      <tr>
        <td>Monsters</td>
        <td>
          <img decoding="async" src="https://via.placeholder.com/40/black" alt="">
        </td>
        <td>Mohamed <br>Ibrahim </td>
        <td>n@nn.sa</td>
        <td>&reg;</td>
        <td>
          <a href="profile.com">Profile</a>
        </td>
      </tr>
      <tr>
        <td colspan="5">Total members</td>
        <td>3</td>
      </tr>
    </table>
  </body>
</html>
```

### Q2
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    <table border="1" cellpadding="10px">
      <caption>Table Caption</caption>
      <tr>
        <th>Date</th>
        <th>Name</th>
        <th>Points</th>
      </tr>
      <tr>
        <td rowspan="4">Month</td>
        <td>Osama Mohamed</td>
        <td>100</td>
      </tr>
      <tr>
        <td>Sayed Mohamed</td>
        <td>100</td>
      </tr>
      <tr>
        <td>Ahmed Mohamed</td>
        <td>100</td>
      </tr>
      <tr>
        <td>Eman Mohamed</td>
        <td>100</td>
      </tr>
    </table>
  </body>
</html>
```

### Q3
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    <table border="1" cellpadding="15px">
      <caption>Complex table</caption>
      <tr>
        <th>Year</th>
        <th>Group</th>
        <th>Language</th>
        <th>Done</th>
        <th>Passed</th>
      </tr>
      <tr>
        <td rowspan="5">2022</td>
        <td rowspan="2">Elzero</td>
        <td>HTML</td>
        <td colspan="2">Yes</td>
      </tr>
      <tr>
        <td>CSS</td>
        <td colspan="2">Yes</td>
      </tr>
      <tr>
        <td rowspan="3">Heroes</td>
        <td>JS</td>
        <td>Yes</td>
        <td>No</td>
      </tr>
      <tr>
        <td>PHP</td>
        <td colspan="2">Yes</td>
      </tr>
      <tr>
        <td>Python</td>
        <td>No</td>
        <td>No</td>
      </tr>
    </table>
  </body>
</html>
```

### Q4
   * Not Documented Yet!

### Q5
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    <header>
      <h1>title</h1>
      <a href="#home">home</a>
      <a href="#about">about</a>
      <a href="#contact">contact</a>
      <a href="#product">product</a>
      <a href="#portifolio">portifolio</a>
    </header>
    <nav>
      <a href="#home">home</a>
      <a href="#about">about</a>
      <a href="#contact">contact</a>
      <a href="#product">product</a>
      <a href="#portifolio">portifolio</a>
      <a href="#services">services</a>
    </nav>
    <main>
      <h2>paragraph title</h2>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptate, amet adipisci. Architecto nihil odio aut eligendi totam laboriosam, qui a repellendus sit officia saepe perferendis quis, fugit et ut vel.</p>
      <img src="img.jpg" alt="">
      <a href="#paragraph">read more</a>
      <hr>
      <h2>paragraph title</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam aperiam eum officiis. Excepturi, explicabo illo adipisci aliquam possimus consequuntur maxime non deserunt doloribus tempora esse, quia suscipit sint id voluptatum!</p>
      <img src="img.jpg" alt="">
      <a href="#paragraph">read more</a>
      <hr>
      <h2>paragraph title</h2>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Et quia architecto asperiores sint vitae fugiat dolorum nihil, cupiditate maiores vel neque repudiandae dignissimos, aliquid facilis commodi quis. Voluptatem, velit omnis.</p>
      <img src="img.jpg" alt="">
      <a href="#paragraph">read more</a>
    </main>
    <aside>
      <h2>Categories</h2>
      <ul>
        <li>html</li>
        <li>css</li>
        <li>js</li>
        <li>c++</li>
        <li>c#</li>
      </ul>
    </aside>
    <footer>&copy; Copyright 2021</footer>
  </body>
</html>
```

### Q6
```html
<audio controls autoplay loop>
  <source src="song.mp3" type="audio/mpeg">
  <source src="song.wav" type="audio/wav">
  <source src="song.ogg" type="audio/ogg"> your browser doesn't support audio files
</audio>
```

### Q7
```html
<video controls autoplay loop muted poster="imgs/home/cover-speed-website.png">
  <source src="song.mp4" type="audio/mpeg">
  <source src="song.ogg" type="audio/ogg">
  <source src="song.mkv" type="audio/mkv"> your browser doesn't support video files
  <track src="my_file_en.vtt" kind="subtitles" srclang="en" label="English">
  <track src="my_file_it.vtt" kind="subtitles" srclang="it" label="Italian">
</video>
```

### Q8
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    <form action="test.py" method="post">
      <label for="user">UserName</label>
      <input type="text" name="user" id="user" placeholder="UserName" required>
      <hr>
      <label for="pass">Password</label>
      <input type="password" name="pass" id="pass" placeholder="enter your password">
      <hr>
      <label for="phone">Phone</label>
      <input type="tel" name="phone" id="phone" pattern="[0-9]{3} [0-9]{3} [0-9]{5}">
      <hr>
      <label for="email">Email</label>
      <input type="email" name="email" id="email" required>
      <hr>
      <input type="reset" value="empty form">
      <input type="submit" value="send data">
    </form>
  </body>
</html>
```

### Q9
```html
<input type="range" value="400" min="100" max="500">
```
