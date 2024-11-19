## Template Instructions:

### (2) About Section

- On `<p>` tag with class name `.about-wrapper__info-text`, include information about you, I recommend to put 2 paragraphs in order to work well and a maximum of 3 paragraphs.


### (3) Projects Section

- Each project lives inside a `row`.
- On `<h3>` tag with class name `.project-wrapper__text-title`, include your project title.
- On `<p>` tag with `loremp ipsum` text, include your project description.
- On first `<a>` tag, put your project url on `href` property.
- On second `<a>` tag, put your project repository url on `href` property.

---

- Inside `<div>` tag with class name `.project-wrapper__image`, put your project image url on the `src` of the `<img>` and put again your project url in the `href` property of the `<a>` tag.
- Recommended size for project image (1366 x 767), your project image must be located inside `/src/assets/` folder.

```html
<!-- **** Projects Section **** -->
<section id="projects">
  ...
  <!-- Notice: each .row is a project -->
  <div class="row">
    <div class="col-lg-4 col-sm-12">
      <div class="project-wrapper__text load-hidden">
        <h3 class="project-wrapper__text-title">Project Title</h3>
        <div>
          <p class="mb-4">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Excepturi
            neque, ipsa animi maiores repellendus distinctio aperiam earum dolor
            voluptatum consequatur blanditiis inventore debitis fuga numquam
            voluptate ex architecto itaque molestiae.
          </p>
        </div>
        <a
          rel="noreferrer"
          target="_blank"
          class="cta-btn cta-btn--hero"
          href="#!"
        >
          See Live
        </a>
        <a
          rel="noreferrer"
          target="_blank"
          class="cta-btn text-color-main"
          href="#!"
        >
          Source Code
        </a>
      </div>
    </div>
    <div class="col-lg-8 col-sm-12">
      <div class="project-wrapper__image load-hidden">
        <a rel="noreferrer" href="#!" target="_blank">
          <div
            data-tilt
            data-tilt-max="4"
            data-tilt-glare="true"
            data-tilt-max-glare="0.5"
            class="thumbnail rounded js-tilt"
          >
            <img
              alt="Project Image"
              class="img-fluid"
              src="assets/project.jpg"
            />
          </div>
        </a>
      </div>
    </div>
  </div>
  <!-- /END Project -->
  ...
</section>
```

### (5) Footer Section

- If you an additional Social Media account different than Twitter, Linkedin or GitHub, then go to [Font Awesome Icons](https://fontawesome.com/v4.7.0/icons/) and search for the icon's class name you are looking.
- You can delete or add as many `<a>` tags your want.

```html
<footer class="footer navbar-static-bottom">
  ...
  <div class="social-links">
    <a href="#!" target="_blank">
      <i class="fa fa-twitter fa-inverse"></i>
    </a>
    <a href="#!" target="_blank">
      <i class="fa fa-linkedin fa-inverse"></i>
    </a>
    <a href="#!" target="_blank">
      <i class="fa fa-github fa-inverse"></i>
    </a>
  </div>
  ...
</footer>
```

### Step 2 - STYLES

Change the color theme of the website - (choose 2 colors to create a gradient)

Go to `/src/sass/abstracts/_variables.scss` and only change the values for this variables `$main-color` and `$secondary-color` with your prefered HEX color.
If you want to get some gradients inspiration I highly recommend you to check this website [UI Gradient](https://uigradients.com/#BrightVault)

```scss
// Default values
$main-color: #02aab0;
$secondary-color: #00cdac;
```

---

## Deployment 📦

[Netlify](https://netlify.com)


## Technologies used 🛠️

- [Parcel](https://parceljs.org/) - Bundler
- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Frontend component library
- [Sass](https://sass-lang.com/documentation) - CSS extension language
- [ScrollReveal.js](https://scrollrevealjs.org/) - JavaScript library
- [Tilt.js](https://gijsroge.github.io/tilt.js/) - JavaScript tiny parallax library


## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
