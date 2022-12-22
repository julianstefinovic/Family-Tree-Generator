# Family-Tree-Generator
A Python3 Jupyter Notebook to convert a family tree text-file to a graphical visualisation.

This project allows the user to enter a text file the format specificed below to create a Family Tree visualisation. 
The visualisation can handle large family trees, tested up to 1500 entries maintaining high resolution.
An example textfile needs to look as follows:

```
1. Abraham SIMPSON (b.1937)
sp: Mona STWEWART (b.1940)
  |-2. Herb SIMPSON
  |-2. Homer SIMPSON (b.1967, m.1996)
  | sp: Marge BOUVIER (b.1971, m.1996)
  |  |-3. Bart SIMPSON (b.1997)
  |  |-3. Lisa SIMPSON (b.1999)
  |  |-3. Maggie SIMPSON (b.2005)
```

This produces the following output: 
![simspons_family_tree](https://user-images.githubusercontent.com/57871364/209159260-ca6e1f6e-bc31-45dc-8350-22640448116f.png)
