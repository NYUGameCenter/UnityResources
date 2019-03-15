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
-   [Pooling](#pooling)
-   [Tweening](#tweening)

## Documentation

#### What's documentation?

#### Why use it?

### User Contributed Notes for Unity Docs

#### What is this?

It's a Chrome Plugin to add user comments to the Unity documentation pages.

#### Why use it?

Unity documentation, like most documentation, is often incomplete, sometimes confusing, and sometimes straight up wrong. User comments can save you from making mistakes based on bad documentation.

-   https://chrome.google.com/webstore/detail/user-contributed-notes-fo/fchdfdnnpkphopmdaochdfnmcahndmnb

## Editor GUI

#### What's Editor GUI?

#### Why use it?

### Naughty Attributes

-   https://github.com/dbrizov/NaughtyAttributes

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

-   https://gist.github.com/quill18/5a7cfffae68892621267

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
-   [Easing Functions Cheat Sheet](#EasingFunctionsCheatSheet)

### DOTween

-   http://dotween.demigiant.com/

#### What is this?

DOTween is the most commonly used tweening library at the Game Center.

#### Why use it?

Its very powerful & simple to use at first.

#### Warnings?

If you choose to venture deeper into its powerful features, the syntax can be a little odd if you're coming from writing mostly c# for Unity, as it more closely resembles modern Javascript.

### LeanTween

-   https://assetstore.unity.com/packages/tools/animation/leantween-3595

#### What is this?

LeanTween is another commonly used tweening library.

#### Why use it?

It's a good alternative to DOTween, and it's useful to know about as it may be used in other code or projects you see online.

### Easing Functions Cheat Sheet

-   https://easings.net/

#### What is this?

The easing functions cheat sheet is a visualization of many of the more common easing functions.

### Why use it?

Sometimes it can be hard to remember how a particular tween looks - this gives an easy to use reference.

Examples:
