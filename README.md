# What's going on here?

Per students' request, let's create a big list of Unity resources. (There will also be another list of non-unity game dev resources.) Right now, this is very much a work in progress.

I've started by collecting resources & starting to sort them. I've been stubbing in simple explanations for each category; I think we'll want to keep those going. My preference is not to overwhelm with options, & to present multiple options for the same functionality only when there are _very strong reasons_ to do so. In this way, I hope the list can be more useful than the "Other Lists Like This" below, which tend to be exhaustive & poorly pruned. That said, using those lists for research & inspiration is encouraged!

Other Lists Like This

-   http://www.unitylist.com/
-   https://github.com/RyanNielson/awesome-unity
-   https://www.virtualgamelab.com/blog/unity-resources

# Contents

-   [Documentation](#documentation)
-   [Builds](#builds)
-   [Editor GUI](#editor-gui)
-   [Pooling](#object-pooling)
-   [Tweening](#tweening)
-   [Shaders](#shaders)
-   [Git](#git)
-   [Controllers and Input](#controllers-and-input)
-   [AI](#ai)
-   [Tutorials](#tutorials)

## Documentation

#### What's documentation?

Explanation of documentation here.

#### Why use it?

### User Contributed Notes for Unity Docs ([Link](https://chrome.google.com/webstore/detail/user-contributed-notes-fo/fchdfdnnpkphopmdaochdfnmcahndmnb))

#### What is this?

It's a Chrome Plugin to add user comments to the Unity documentation pages.

#### Why use it?

Unity documentation, like most documentation, is often incomplete, sometimes confusing, and sometimes straight up wrong. User comments can save you from making mistakes based on bad documentation.

## Builds

#### What's a build?

It's a sharable version of your unity game, built for a particular platform (windows, iOS, etc.).

#### Why use it?

So you can share your work with others or sell it.

### Super Unity Build ([Link](https://github.com/Chaser324/unity-build))

![Preview](https://github.com/NYUGameCenter/UnityResources/blob/master/Images/SuperUnityBuild.png)

#### What is this?

It's a unity asset that makes building for various platforms & uploading builds to sites like itch.io very easy.

#### Why use it?

It saves you time, saves you from having to do a multi-step upload process every time you build. 

## Editor GUI

#### What's Editor GUI?

It's how component are drawn in the unity inspector. It's very customizable, but can be arduous to impliment.

#### Why use it?

Custom editor tools can enable huge improvements to workflow, enable easier testing, and make collaboration easier.

### Naughty Attributes ([Link](https://github.com/dbrizov/NaughtyAttributes))

![Example Button](https://github.com/NYUGameCenter/UnityResources/blob/master/Images/NaughtyAttributes.png)

#### What is this?

It's a library for Unity that makes it very easy to create simple buttons, lists, etc. in the Unity Inspector.

#### Why use it?

Writing Unity Editor code is tough & time consuming. Often all you want is a simple button to run a function, but that usually requires creating a whole new script. With Naughty Attributes, it's super simple.

## Object Pooling

#### What's object pooling?

#### Why pool your objects?

You're running into memory limits or garbage collection hitches & want to ensure smooth gameplay.

### Simple Pool Script ([Link](https://gist.github.com/quill18/5a7cfffae68892621267)) - A simple and lightweight pool script.

## Tweening

#### What's a tweening library?

A Tweening library is a set of extensions for Unity focused on animating values across a number frames.

#### Why use it?

Tweening can save you from writing timers, dealing with tons of lerps[TODO: Link], or using coroutines.

#### DoTween:

-   [DOTween](http://dotween.demigiant.com/) - DOTween is the most commonly used tweening library at the Game Center. Its very powerful & simple to use at first. However, if you choose to venture deeper into its powerful features, the syntax can be a little odd if you're coming from writing mostly c# for Unity, as it more closely resembles modern Javascript.

#### Additional Resources:

-   [Easing Functions Cheat Sheet](https://easings.net/) - The easing functions cheat sheet is a visualization of many of the more common easing functions. Sometimes it can be hard to remember how a particular tween looks - this gives an easy to use reference.

## Git ([Link](https://git-scm.com/))

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

### NYU Unity Git Config ([Link](https://github.com/NYUGameCenter/Unity-Git-Config))

Whenever possible, it's always recommended to use the NYU Unity Git Config, as it will help prevent common issues using Git with Unity. Follow these instructions _exactly_, and make sure you do them all!

### GitHub([Link](http://www.github.com))

-   GitHub is a free git repository hosting service. GitHub provides a Web-based graphical interface, as well as access control and several collaboration features, such as a wikis and basic task management tools.

### Git GUI

When you're first starting with git, it can often be useful to use a GUI, or Graphical User Interface, as a way of visualizing what's happening. Below are some good, free options that work on Mac and Windows.

-   [GitKraken](https://www.gitkraken.com/)
-   [SourceTree](https://www.sourcetreeapp.com/)

### Additional Resources:

-   [Learn Git Branching](https://learngitbranching.js.org/) - A straightforward tutorial on how branching in git works.
-   [Git: The Simple Guide](http://rogerdudler.github.io/git-guide/) - A simple explanation of how to use git from the command line.
-   [Don't Be Afraid To Commit](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html) - A good primer on using Git from the command line.

## Controllers and Input

-   [InControl](https://assetstore.unity.com/packages/tools/input-management/incontrol-14695)

## Shaders

-   [Amplify Shader Editor](https://assetstore.unity.com/packages/tools/visual-scripting/amplify-shader-editor-68570) - A _PAID_ asset that helps visualize creating shaders.

## AI

-   [A\* Pathfinding](http://arongranberg.com/astar/)

## Tutorials and Further Resources

Below is a list of some helpful, Unity-specific tutorials.

### General Tutorials and Resources

-   [Unity Blog](https://blogs.unity3d.com/) - Straight from the source itself, the Unity3D blog often has tutorials on a variety of topics. Unity also provides a set of [video tutorials](http://unity3d.com/learn/tutorials/modules) that are well worth checking out.
-   [What Not To Do In Unity](https://unity3d.com/how-to/unity-common-mistakes-to-avoid) - Unity3D has also put together a useful list of common mistakes in Unity.
-   [50 Tips and Best Practices](http://www.gamasutra.com/blogs/HermanTulleken/20160812/279100/50_Tips_and_Best_Practices_for_Unity_2016_Edition.php) - A good list of best practices for working in Unity.

### Programming Tutorials and Resources

-   [Gameplay Programming Patterns](http://gameprogrammingpatterns.com/) - A great resource on programming for games, useful in Unity and any other engine.

### Shaders and Graphics Tutorials and Resources

-   [Optimizing Graphics Performance](https://docs.unity3d.com/Manual/OptimizingGraphicsPerformance.html) - A good Unity-provided list of how to avoid common graphics issues
-   [Catlike Coding](https://catlikecoding.com/unity/tutorials/) - A great set of tutorials on how shaders work in Unity.
-   [A gentle introduction to shaders in Unity3D](https://www.alanzucconi.com/2015/06/10/a-gentle-introduction-to-shaders-in-unity3d/) - A series of easy-to-digest tutorials in shaders for Unity by Alan Zucconi.
