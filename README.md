# Modern Login Component

A static login component built with HTML and CSS. Features clean design with username/password fields, remember me option, and password recovery. Simple and ready to implement in any web project.


## Features

- Clean, modern UI design
- Username and password input fields
- "Remember me" functionality
- "Forgot password" recovery option
- New user signup redirection
- Built with only HTML and CSS 

## Usage

1. Clone the repository:
```
git clone https://github.com/elifbaskurt/modern-login-component.git
```

2. Include the necessary CSS files in your project
3. Copy the HTML structure into your project

## Example HTML Structure

```html
<div class="login-container">
  <!-- Welcome Banner -->
  <div class="welcome-banner">
    <h2>Welcome Back!</h2>
    <p>Sign in to continue</p>
    <!-- Avatar illustrations -->
  </div>
  
  <!-- Login Form -->
  <form class="login-form">
    <div class="form-group">
      <label for="username">Username</label>
      <input type="text" id="username" placeholder="Enter username">
    </div>
    
    <div class="form-group">
      <label for="password">Password</label>
      <input type="password" id="password" placeholder="Enter Password">
    </div>
    
    <div class="form-options">
      <div class="remember-me">
        <input type="checkbox" id="remember">
        <label for="remember">Remember me</label>
      </div>
    </div>
    
    <button type="submit" class="login-btn">Log In</button>
    
    <div class="additional-options">
      <a href="#" class="forgot-password">Forgot your password</a>
      <p class="signup">Don't have an account? <a href="#">Signup now</a></p>
    </div>
  </form>
  
  <div class="footer">
    <p>©2020 Crafted and designed by elifbaskurt.</p>
  </div>
</div>
```

## Customization

You can easily customize the colors, fonts, and spacing by modifying the CSS variables in the stylesheet.

## License

MIT

## Author

[elifbaskurt](https://github.com/elifbaskurt)
