# flat-module
Yet another method for modular JS

What is this?

A file inside a folder under git.

What can I do with it? 

Execute the file to create a sibling folder with a name of your choosing, containing the same file, and also under git.

Why should I do that?

You coded something. It got bigger. You added a dependency. The dependency became a tree of dependencies. You lost overview. The package manager took care of that and loads all the stuff recursively. Your folder is now ~100GB in size. 

But that is not necessary! 

When you start coding, it is just one module. When it gets bigger, that module can spawn a new module. The two are siblings, fundamentally equal. But they can still work together, because the first module knows the second and vice-versa. You can keep them locally or on a git hoster. You can start from any one of them and retrieve all the others from their remote locations.

When you start coding and need another already existing module, you just clone it from its remote right next to your module. That's you external dependency.
