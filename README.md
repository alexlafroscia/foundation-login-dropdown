# Foundation Login Dropdown

Provides the markup required for a login dropdown in [Foundation 5](https://github.com/zurb/foundation).

It tries to provide as much support for Foundation's responsiveness as it can, adjusting the width of the input fields in the mobile view's menu.  It also makes adjustments if the input field is the topmost element in the dropdown.

## Usage

###### 1. Clone the project to install it

```bash
git clone git@github.com:alexlafroscia/foundation-login-dropdown.git
```

###### 2. Include it in your Sass

Import it to the top of your file, after Foundation

```sass
@import "foundation-login-dropdown";
```

Done. Easy as pie.

## HTML Structure

Below is an example of the HTML structure that provides a username field, password field, and confirmation button.

```html
<li class="has-dropdown">
  <a href="#">Login</a>
  <ul class="dropdown">
    <li><input type="text" placeholder="Username"></li>
    <li><input type="password" placeholder="Password"></li>
    <li><a href="#" class="button alert">Login</a></li>
  </ul>
</li>
```

***

I'll update this as I come up with improvements.  Thanks for checking it out!

If you have any questions or want to get in touch, you can find me on Twitter: [@alexlafroscia](https://twitter.com/AlexLaFroscia)