<h1>
  <span class="headline">Cozy Cafe Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Open your Terminal application and navigate to your **`~/code/ga/labs`** directory:

```bash
cd ~/code/ga/labs
```

Navigate to [GitHub](https://github.com/) and create a new repository named **cozy-cafe-lab**.

- Make sure the repo is set to `public`
- You do not need a `README.md`
- You do not need a `.gitignore`

Using the `Quick Setup` option, clone your newly created repo into your `~/code/ga/labs` directory with the `git clone` command:

```bash
git clone https://github.com/<your-username>/cozy-cafe-lab.git
```

> Note: In the link above, where it says `<your-username>`, you should see the username from your GitHub account.

Next, `cd` into your new cloned directory, `cozy-cafe-lab`:

```bash
cd cozy-cafe-lab
```


Create a directory called `js`:

```bash
mkdir js
```

Then, create an `index.html` file, as well as a `app.js` file inside the `js` directory. These files will hold your work for this lab:

```bash
touch index.html ./js/app.js
```

With the files created, open the contents of the directory in VS Code:

```bash
code .
```

### HTML

Add the following to your **`index.html`** file.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Cozy Cafe</title>
    <script defer src="./js/app.js"></script>

    <style>
        header{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        #bg-color-btn{
            background-color: rgb(149, 129, 65);
            color: black;
            border: 0;
            border-radius: 5%;
            height: 3rem;
        }

        #bg-color-btn:hover{
            padding: 10px;
            background-color: rgb(124, 107, 53);

        }
    </style>

  </head>
  <body>

    <header>
        <h1 id="main-title">Welcome to the Cozy Cafe - Where Flavors and Comfort Meet</h1>
        <button id="bg-color-btn">Change Background Color</button>
    </header>

    <h4>Cafe Specialties</h4>
    <ul id="cafe-specialties">
      <li>Rose Latte</li>
      <li>Pistachio Croissant</li>
      <li>Lotus Cheesecake</li>
    </ul>

    <h4>Our Cafe Moments</h4>
    <img class="cafe-photo" alt="photo" style="width: 30vh;" src="https://images.pexels.com/photos/8526416/pexels-photo-8526416.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2">
    <img class="cafe-photo" alt="photo" style="width: 30vh;" src="https://images.pexels.com/photos/8526484/pexels-photo-8526484.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2">
    <img class="cafe-photo" alt="photo" style="width: 30vh;" src="https://images.pexels.com/photos/8526401/pexels-photo-8526401.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2">
    <img class="cafe-photo" alt="photo" style="width: 30vh;" src="https://images.pexels.com/photos/8526404/pexels-photo-8526404.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2">
    <img class="cafe-photo" alt="photo" style="width: 30vh;" src="https://images.pexels.com/photos/11160127/pexels-photo-11160127.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2">

    <h1 class="highlight-title">Quote of the Day:</h1>
    <p id="quote-of-the-day"></p>

    <hr />

    <section id="blogs">
        <h1 class="highlight-title">Cafe Adventures</h1>
        <div class="blog-post">
            <h3>Weekend Brunch Special</h3>
            <p>We featured our new pistachio pancakes, and they were a crowd favorite!</p>
        </div>
        <div class="blog-post">
            <h3>Live Music Night</h3>
            <p>Our cafe was filled with beautiful melodies, making it an unforgettable evening.</p>
        </div>
    </section>

    <hr />

    <h4>Past Menu Items</h4>
    <ul id="past-menu-items">
      <li>Vanilla Chai Muffin</li>
      <li>Fish Tacos</li>
      <li>Spiced Apple Cider</li>
      <li>Honey Almond Tart</li>
    </ul>

  </body>
</html>
```


- Open the **`index.html`** file in your browser and access the console output in your browser's dev tools to begin work on your JavaScript logic.