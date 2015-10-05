<h3>Styling</h3>

The repo contains styling for an app to be implemented in future.</br></br>
Styles are written in SCSS and placed in the `scss` directory. In order to transpile the styles into `css` format, please follow the steps listed below.</br></br>
First, install the `sass` gem:</br>
```
gem install sass
```
</br>
You can manually transpile files with the following command run from the `styling` directory (`index` is an exemplary file name):
```
sass scss/index.scss css/index.css
```
</br>
Or you can set a watcher that will automatically convert `scss` files to `css` once it notices any changes in the code.
You may point a specific file to be watched:
```
sass --watch scss/index.scss:css/index.css
```

Or specify the whole folder for the watcher to track changes:
```
sass --watch scss:css
```
