# Design

Sublime Network is a fast and scalable multiplayer game server for unity3d and unreal engine 4 games. Sublime Network was designed for high concurrent users through multi server architecture while maintaning ease of use. Create a large world spread out over multiple servers and seamlessly transitio between them. Or create a scalable and robust match based games. 

## Features
Some of its key features include
* Only pay for what you use.
  * The Modular design of Sublime Network makes it so if you don't need a feature it can be unloaded
  leaving you with 0 overhead for systems not in use.
* Run your server without a unity or unreal instance. To save prescious resources.
  * Server side physics.
  * Server side navigation. Easily generate your servers navmesh with the click of a button.
* Seamlessly transition entities to different servers in order to scale your world indeffinately.
  * Automatic zone tranistions. You don't have to code this behavior in. Just configure your zones.
* Interest management through spatial hashing.
  * Easily configure how often and when entities interact over the network
* Server side scripting with Pawn.
  * Compiler can automatically 
  * Pawn is a FAST typeless scripting language that forces you to write data oriented code.
  * No garbage collector so you don't have to worry about stutters.
  * No need for memeory management.
  * Simple easy to use c like syntax. 
* Save bandwidth with protocol buffers.
* Code generator to save time writing bootstrap code.
* The plugin system allows you to easily extend Sublime Network as well as disable unused modules to save resources.
* Flow graph script editor(similar to unreal engine 4s blueprints) that generates optimized pawn scripts.(Still a work in progress)
  * When this is finished pawn will start building as assembler instead of byte code making it run event faster.

This is only some of Sublime Networks features. There is much more included and features are being added daily.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SublimeCreations/SublimeNetwork/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
