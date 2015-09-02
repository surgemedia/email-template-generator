#Email Tempalte Generator

This builder is made to help create a static sites employing the DRY concept of coding.

##Setup in terminal
- `sudo npm install` *can take a few mins*
- `sudo bower install`
- `gulp`
- upload the `render/` is your file site

##Assets 
- found under `cwd/assets/*` 
- convert to `render/assets/*`

##HTML
Using what ever structure you want just update the gulp js file.

##Frameworks 
- [Bower](http://bower.io/)
- [gulpjs](http://gulpjs.com/)
- [Sass](http://sass-lang.com/)
- [Npm](https://www.npmjs.com/)
- [Nodejs](https://nodejs.org/)
- Juice?
- HTML TAG


###Includes
found under `cwd/includes` set as base for includes here is some example include code

```
			@@include('h1.html',{
                "text": "Hello World"
                });
``` 


Html includes allow variables like so this would be `h1.html`


```html
<h1>@@text</h1>
```

this would render


```html
<h1>Hello World</h1>
```



- `cwd/assets/sass/*.less`
- `bower_components/sass/*less` = `render/skin.css`


- `cwd/assets/js/*.js`
-`bower_components/js/*js` = `render/skin.css`


##Gulp
###Commands
Only 1 command so far `gulp`
*more coming soon*

###Installation Progress###
Install node.js (windows, linux, mac)
- npm install
- bower install
- gulp
- gulp watch
Dependiences
