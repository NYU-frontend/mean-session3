#MEAN Session Three

##Assignment
Add the necessary Angular code to the Pirate Portfolio (ng-app, ng-init, ng-model) to make the existing input field behave as it does in the sample angular js file we worked on in class. Be sure to download version3 - the latest repo - mean-session3/other/Angular/start.html. Here's the html doc - copy and paste it if you don't feel like digging!
```
<html ng-app>
<head>
  <link rel="stylesheet" type="text/css" href="https://netdna.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
	<script src="https://code.angularjs.org/1.3.0-rc.1/angular.min.js"></script>
</head>

<body style="padding: 50px" ng-init="messageText = 'Hello World!'">
  <div class="alert alert-success">
    <input ng-model="messageText" size="30"/><br/>
    Everybody wanna shout "{{ messageText | uppercase }}"
  </div>
</body>

</html>
```

##Tools of the trade - continued

Github
```
git init
git add .
git commit -m 'message here'
git push -u origin master
git branch version2
git checkout version2

git config --global user.name "username"
git config --global user.email "you@email.com"
```
* [Github forking](https://help.github.com/articles/fork-a-repo/) 
* [Github commenting](https://help.github.com/articles/markdown-basics/)

Git  
* [Git checkout](http://git-scm.com/docs/git-checkout)
* [Git branch](http://git-scm.com/docs/git-branch)
* [Git push](http://git-scm.com/docs/git-push)

Other
* [Google fonts](https://www.google.com/fonts)
* [SASS features](http://sass-lang.com/guide): nesting, operators and the difference between SASS and SCSS
* Responsive design: breakpoints and images
* CSS pseudo selector: before
* CSS clearfix, sprites and animation 

##Objectives

Understand the basic principles of jQuery. This session will cover:

* jQuery effects on the page (DOM manipulation - menus and accordion)
* The problem with jQuery for SPAs (Single page applications)
* The Chrome Web Developer tool
* [Package control](https://packagecontrol.io/) and [Emmet](http://emmet.io/) for [Sublime Text](http://www.sublimetext.com/)
* Git branching and other workflow issues

##Essentials
```
python -m SimpleHTTPServer
```
