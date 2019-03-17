# What's going on here?

Per students' request, let's create a big list of Unity resources. (There will also be another list of non-unity game dev resources.) Right now, this is very much a work in progress.

I've started by collecting resources & starting to sort them. I've been stubbing in simple explanations for each category; I think we'll want to keep those going. My preference is not to overwhelm with options, & to present multiple options for the same functionality only when there are _very strong reasons_ to do so. In this way, I hope the list can be more useful than the "Other Lists Like This" below, which tend to be exhaustive & poorly pruned. That said, using those lists for research & inspiration is encouraged!

Other Lists Like This

-   http://www.unitylist.com/
-   https://github.com/RyanNielson/awesome-unity
-   https://www.virtualgamelab.com/blog/unity-resources

# Contents

-   [Documentation](#documentation)
-   [Editor GUI](#editor-gui)
-   [Pooling](#object-pooling)
-   [Tweening](#tweening)
-   [Git](#git)
-   [Tutorials](#tutorials)

## Documentation

#### What's documentation?

#### Why use it?

### User Contributed Notes for Unity Docs ([Link](https://chrome.google.com/webstore/detail/user-contributed-notes-fo/fchdfdnnpkphopmdaochdfnmcahndmnb))

#### What is this?

It's a Chrome Plugin to add user comments to the Unity documentation pages.

#### Why use it?

Unity documentation, like most documentation, is often incomplete, sometimes confusing, and sometimes straight up wrong. User comments can save you from making mistakes based on bad documentation.

## Editor GUI

#### What's Editor GUI?

#### Why use it?

### Naughty Attributes ([Link](https://github.com/dbrizov/NaughtyAttributes))

#### What is this?

It's a library for Unity that makes it very easy to create simple buttons, lists, etc. in the Unity Inspector.

#### Why use it?

Writing Unity Editor code is tough & time consuming. Often all you want is a simple button to run a function, but that usually requires creating a whole new script. With Naughty Attributes, it's super simple.

Example:
![Example Button Code](https://github.com/dbrizov/NaughtyAttributes/raw/master/Assets/Plugins/NaughtyAttributes/Documentation/Button_Code.PNG)
![Example Button](https://github.com/dbrizov/NaughtyAttributes/raw/master/Assets/Plugins/NaughtyAttributes/Documentation/Button_Inspector.PNG)

## Object Pooling

#### What's object pooling?

#### Why pool your objects?

### Simple Pool Script ([Link](https://gist.github.com/quill18/5a7cfffae68892621267))

#### What is this?

A simple and lightweight pool

#### Why use it?

You're running into memory limits or garbage collection hitches & want to ensure smooth gameplay.

## Tweening

#### What's a tweening library?

A Tweening library is a set of extensions for Unity focused on animating values across a number frames.

#### Why use it?

Tweening can save you from writing timers, dealing with tons of lerps[TODO: Link], or using coroutines.

#### Resources:

-   [DOTween](#DOTween)
-   [LeanTween](#LeanTween)
-   [Easing Functions Cheat Sheet](#Easing-Functions-Cheat-Sheet)

### DOTween ([Link](http://dotween.demigiant.com/))

#### What is this?

DOTween is the most commonly used tweening library at the Game Center.

#### Why use it?

Its very powerful & simple to use at first.

#### Warnings?

If you choose to venture deeper into its powerful features, the syntax can be a little odd if you're coming from writing mostly c# for Unity, as it more closely resembles modern Javascript.

### LeanTween ([Link](https://assetstore.unity.com/packages/tools/animation/leantween-3595))

#### What is this?

LeanTween is another commonly used tweening library.

#### Why use it?

It's a good alternative to DOTween, and it's useful to know about as it may be used in other code or projects you see online.

### Easing Functions Cheat Sheet ([Link](https://easings.net/))

#### What is this?

The easing functions cheat sheet is a visualization of many of the more common easing functions.

### Why use it?

Sometimes it can be hard to remember how a particular tween looks - this gives an easy to use reference.

## Git ([Link](https://git-scm.com/))

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

### GitHub

-   GitHub is a free git repository hosting service. GitHub provides a Web-based graphical interface, as well as access control and several collaboration features, such as a wikis and basic task management tools.

### Git GUI

When you're first starting with git, it can often be useful to use a GUI, or Graphical User Interface, as a way of visualizing what's happening. Below are some good, free options that work on Mac and Windows.

-   [GitKraken](https://www.gitkraken.com/)
-   [SourceTree](https://www.sourcetreeapp.com/)

### Git Tutorials

-   [Don't Be Afraid To Commit](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html) - A good primer on using Git from the command line.
-   [Learn Git Branching](https://learngitbranching.js.org/) - A straightforward tutorial on how branching in git works.

### NYU Unity Git Config ([Link](https://github.com/NYUGameCenter/Unity-Git-Config))

Whenever possible, it's always recommended to use the NYU Unity Git Config, as it will help prevent common issues using Git with Unity.

## Tutorials

Below is a list of some helpful, Unity-specific tutorials.

### General

-   [Unity Blog](https://blogs.unity3d.com/) - Straight from the source itself, the Unity3D blog often has tutorials on a variety of topics. Unity also provides a set of [video tutorials](http://unity3d.com/learn/tutorials/modules) that are well worth checking out.
-   [What Not To Do In Unity](https://unity3d.com/how-to/unity-common-mistakes-to-avoid) - Unity3D has also put together a useful list of common mistakes in Unity.
-   [50 Tips and Best Practices](http://www.gamasutra.com/blogs/HermanTulleken/20160812/279100/50_Tips_and_Best_Practices_for_Unity_2016_Edition.php) - A good list of best practices for working in Unity.

### Programming

-   [Gameplay Programming Patterns](http://gameprogrammingpatterns.com/) - A great resource on programming for games, useful in Unity and any other engine.

### Shaders and Graphics

-   [Optimizing Graphics Performance](https://docs.unity3d.com/Manual/OptimizingGraphicsPerformance.html) - A good Unity-provided list of how to avoid common graphics issues
-   [Catlike Coding](https://catlikecoding.com/unity/tutorials/) - A great set of tutorials on how shaders work in Unity.
-   [A gentle introduction to shaders in Unity3D](https://www.alanzucconi.com/2015/06/10/a-gentle-introduction-to-shaders-in-unity3d/) - A series of easy-to-digest tutorials in shaders for Unity by Alan Zucconi.
