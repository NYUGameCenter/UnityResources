# What's going on here?

Per students' request, I'm creating a big list of Unity resources. (There will also be another list of non-unity game dev resources.) This is very much a work in progress. Right now, just collecting resources & starting to sort them. I've been stubbing in simple explanations for each category; I think we'll want to keep those going. My preference is not to overwhelm with options, & to present multiple options only when there are very strong reasons to do so. In this way, the list can be more useful than the "Other Lists Like This" below, which tend to be exhaustive & poorly pruned. However, using those lists for research & inspiration is encouraged!


Other Lists Like This
- http://www.unitylist.com/
- https://github.com/RyanNielson/awesome-unity
- https://www.virtualgamelab.com/blog/unity-resources


## Documentation
#### What's documentation?
#### Why use it?

### User Contributed Notes for Unity Docs
#### What is this?
It's a Chrome Plugin to add user comments to the Unity documentation pages.
#### Why use it?
Unity documentation, like most documentation, is often incomplete, sometimes confusing, and sometimes straight up wrong. User comments can save you from making mistakes based on bad documentation.
- https://chrome.google.com/webstore/detail/user-contributed-notes-fo/fchdfdnnpkphopmdaochdfnmcahndmnb


## Editor GUI
#### What's Editor GUI?
#### Why use it?

### Naughty Attributes 
- https://github.com/dbrizov/NaughtyAttributes
#### What is this?
It's a library for Unity that makes it very easy to create simple buttons, lists, etc. in the Unity Inspector.
#### Why use it?
Writing Unity Editor code is tough & time consuming. Often all you want is a simple button to run a function, but that usually requires creating a whole new script. With Naughty Attributes, it's super simple.

Example:
![Example Button Code](https://github.com/dbrizov/NaughtyAttributes/raw/master/Assets/Plugins/NaughtyAttributes/Documentation/Button_Code.PNG)
![Example Button](https://github.com/dbrizov/NaughtyAttributes/raw/master/Assets/Plugins/NaughtyAttributes/Documentation/Button_Inspector.PNG)

## Pooling
#### What's object pooling?
#### Why pool your objects?

### Simple Pool Script

- https://gist.github.com/quill18/5a7cfffae68892621267
#### What is this?
A simple and lightweight pool
#### Why use it?
You're running into memory limits or garbage collection hitches & want to ensure smooth gameplay.


## Tweening
#### What's a tweening library?
A Tweening library is a set of extensions for Unity focused on animating values across a number frames.
#### Why use it?
Tweening can save you from writing timers, dealing with tons of lerps[TODO: Link], or using coroutines.

### DOTween
- http://dotween.demigiant.com/
#### What is this?
DOTween is the most commonly used tweening library at the Game Center. 
#### Why use it?
Its very powerful & simple to use at first. 
#### Warnings? 
If you choose to venture deeper into its powerful features, the syntax can be a little odd if you're coming from writing mostly c# for Unity, as it more closely resembles modern Javascript.

Examples:



