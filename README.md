# Bootstrap Exercise: Build a Responsive Website

## Objective

Create a clean, responsive website using Bootstrap components including a header, navigation bar, cards, form, and footer.

Try to replicate the images inside the `design` directory.

## Instructions

1. **Setup the Project:**
    - Create an HTML file and link to the Bootstrap CDN.

2. **Create the Header:**
    - Add a navigation bar with links. (code already provided)

3. **Main Content:**
    - Add a hero section with a welcome message.
    - Create a card section with three cards. Card image is in the `images` directory.
    - Add a form section for user input.

4. **Footer:**
    - Create a simple footer with links. (code already provided)

5. **Commit and push**

---

## Step-by-Step

### 1. Setup the Project

Create an HTML file named `index.html` and include the Bootstrap CDN.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <title>Bootstrap Exercise</title>
</head>
<body>
  <!-- Header -->
  <!-- Main Content -->
  <!-- Footer -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
```

### 2. Create the Header

Add the navigation and links.

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">MyWebsite</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
```

### 3. Main Content

#### Hero Section

Add a hero section with a welcome message.

```html
<!-- Hero -->
<div class="container my-5">
  <!-- Welcome content here -->
</div>
```

#### Card Section

Create a card section with three cards.

```html
<!-- Cards -->
<div class="container my-5">
  <div class="row">
    <!-- 3 cards go here -->
  </div>
</div>
```

#### Contact Form Section

Create the form section with two fields, one checkbox, and one submit button.

```html
<div class="container my-5">
  <h2>Contact Us</h2>
  <form>
    <div class="mb-3">
      <!-- Email address here -->
    </div>
    <div class="mb-3">
      <!-- Name here -->
    </div>
    <div class="mb-3 form-check">
      <!-- Checkbox here -->
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
</div>
```

### 4. Footer Section

Create a simple footer with links.

```html
<footer class="bg-light text-center text-lg-start">
  <div class="container p-4">
    <div class="row">
      <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
        <h5 class="text-uppercase">Footer Content</h5>
        <p>
          Here you can use rows and columns to organize your footer content.
        </p>
      </div>
      <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
        <h5 class="text-uppercase">Links</h5>
        <ul class="list-unstyled mb-0">
          <li>
            <a href="#!" class="text-dark">Link 1</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 2</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 3</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 4</a>
          </li>
        </ul>
      </div>
      <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
        <h5 class="text-uppercase">Links</h5>
        <ul class="list-unstyled mb-0">
          <li>
            <a href="#!" class="text-dark">Link 1</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 2</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 3</a>
          </li>
          <li>
            <a href="#!" class="text-dark">Link 4</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
  <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
    © 2024 Your Company
  </div>
</footer>
```

### 5. Commit and push

Once you are done, commit and push your changes to your repository.
