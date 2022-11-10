<!-- 
Extra markdown resources
https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md
https://github.com/Ileriayo/markdown-badges
https://shields.io/
https://itopaloglu83.github.io/Jekyll-Markdown-Cheat-Sheet/
https://www.markdownguide.org/cheat-sheet/
https://github.com/tchapi/markdown-cheatsheet
https://github.com/anuraghazra/github-readme-stats
https://linuxize.com/post/gitignore-ignoring-files-in-git/
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
https://www.markdownguide.org/basic-syntax/
https://www.markdownguide.org/extended-syntax/

-->

# Formatting in GitHub
Headings allow you to partition your work cleanly. Each come with a light underline across the entire paragraph for a more clear visual hierarchy. For now this is a lot of copying and pasting examples until I get around to making my own examples.

Helpful resources
 - https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax
 - https://guides.github.com/features/mastering-markdown/
 - https://www.markdownguide.org/basic-syntax/ & https://www.markdownguide.org/extended-syntax/

## Text
There are many things you can do with text. Styling your documents will make them easier to read. Formatting comes in extra handy when you have lots of ideas and want to organize your thoughts in an appealling way.

### Headings
Headings use the `#` symbol to declare a line to be a header. Add one to six `#` symbols before your heading text. The number of `#` you use will determine the size of the heading. Just make sure to leave a space between the hashmarks and your text.

### Linebreaks
Double spaces at the end of the line  
Backslash at the end of the line\
Using the br tag</br>


### Styling
**Bold** needs doulble astrixs.  
*Italic* needs single astrix.  
~~Strikethrough~~ needs double tildas.  

### Code Blocks

``` python
print("This is styled code! Just specify the language at the start")
```

```
print("This is unstyled code. Not as fun.")
```

###
Quotes:
> It seemed like a good idea at the time.  
> Oh well, I'm gonna stick to it!

### Links
This site was built using [GitHub Pages](https://pages.github.com/).

### Lists

#### Unordered Lists
- Butter
- Milk
- Eggs

#### Ordered Lists
1. Item 1
2. Item 2
3. Item 3

#### Nested Lists
To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Atom, you can align your list visually. Type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.
- Primary item
- Primary item
- Primary item
  - Secondary item
    - Tirtiary item
   
#### Task lists
- [x] Task 1
- [ ] Task 2
- [ ] Task 3

## Images

### Embedding
Have a look at a roo:

![Roo](https://www.2gb.com/wp-content/uploads/sites/2/2018/01/Kangaroo-kull.jpg?resize=600%2C400)

## Extras

### Badges
You can make [Badges](https://shields.io/#your-badge). This can probably help you organize and make your content even more appealing!

![Badge](https://img.shields.io/badge/Badge_Name-Text-Blue)
 > `![Badge](https://img.shields.io/badge/Badge_Name-Text-Blue)`
 
 ### Tables
 First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
