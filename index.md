## Design

Sublime Network is a fast and scalable multiplayer game server for unity3d and unreal engine 4 games. Sublime Network was designed for high concurrent users through multi server architecture while maintaning ease of use. Create a large world spread out over multiple servers and seamlessly transitio between them. Or create a scalable and robust match based games. 

Some of its key features include
* Run your server without a unity or unreal instance. To save prescious resources.
  * Server side physics.
  * Server side navigation. Easily generate your servers navmesh with the click of a button.
* Seamlessly transition entities to different servers in order to scale your world indeffinately.
  * Automatic zone tranistions. You don't have to code this behavior in. Just configure your zones.
* Interest management through spatial hashing.
  * Easily configure how often and when entities interact over the network
* Server side scripting with Pawn.
  * Pawn is a FAST typeless scripting language that forces you to write data oriented code.
  * All memory allocations done up front to prevent stutters.
  * Simple easy c like syntax. Without the need to manage memory.
* Save bandwidth with protocol buffers.


 


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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
