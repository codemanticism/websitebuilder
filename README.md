### ![image](https://github.com/codemanticism/websitebuilder/assets/67880895/a986d0f7-4c11-491c-a526-e78234ec690f) Website Builder
Website builder is a browser application that allows you to build websites with HTML and CSS.

I am still building a functionality which will allow for an easily debuggable way to program interactive behaviour, but it's not complete yet, the idea is that you can code anything (markup with HTML + formatting with CSS + interactivity with my own language) and debug it easily with a console window that is baked into the editor. One optimization I want to add is one where only the functions whose code has been changed recompile.

I don't plan in adding syntax highlighting to the editor as the application I am building is simple but if you want to change it just simply

I first decided to do this after having a bad developer experience with [JS Fiddle](https://jsfiddle.net/). In JSFiddle you do not have acess to a decent console, there are no quick debug tools like I want to make and there's no easy way to test a favicon and local saving don't exist, everytime you want to save your progress, you save it on the cloud and that elevates the version number, there's also no autosave whenever you run although there's an optional autosave feature which saves every minute I think but that bumps the version number and is inefficient, everytime you want to run, save your progress, you have to bump up the version number, also sometimes if you for example exit Chrome, it may not save the changes you have made since then.

- [x] You can add and modyify elements
- [X] You can format elements 
- [ ] Save feature
- [ ] Open feature
- [ ] New feature
- [ ] HOME/TEXT
- [ ] Scripting
- [ ] Web Assembly compilation
- [ ] Optimization fixes
Here's how you can use it:

![Github File](https://github.com/codemanticism/websitebuilder/assets/67880895/5f0f5b51-0cfc-4e62-8a91-57554462ab35)

