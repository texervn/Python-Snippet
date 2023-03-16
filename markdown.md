# Some Markdown Tricks

## Define variable link

[github]: https://github.com/texervn
Check you my [Profile][github]

## Thumbnail

[avatar]: https://ps.w.org/basic-user-avatars/assets/icon-128x128.png
[![][avatar]][github]

## Toggle

<details open>
  <summary>
    The content is showed here.
  </summary>
  The actual content goes here.
</details>

<details>
  <summary>
    This content is hidden below.
  </summary>
  The actual content goes here.
</details>

## Table
|First|Second|
|:-:|:-:|
|a|b|

We can also use with images.
|First|Second|
|:-:|:-:|
|![Image 1](https://images.pexels.com/photos/4495796/pexels-photo-4495796.jpeg)|![Image 2](https://images.pexels.com/photos/4495796/pexels-photo-4495796.jpeg)|

## Face Type

**Bold** or __Bold__
*Italic*
~~Strike Through~~
__*Bold Italic*__
Supscript F<sup>p</sup>
Subscript D<sub>x</sub>
==Highlight==

## Quote

Short quote:
> *This is a short quote*

Long quote:
> *This is a long quote.
It has multiple lines.
It has multiple lines. 
It has multiple lines. 
It has multiple lines. 
It has multiple lines. 
It has multiple lines.*

## Latex
We have an equation inline $\sqrt{x^2+y^2} = z$. or

In the middle
$$\sin^2(\alpha)+\cos^2(\beta) = 1.$$
Or
```math
\sin^2(\alpha)+\cos^2(\beta) = 1.
```

## List with check
- [x] Fix Bug 1
- [ ] Add Feature 2
- [ ] Add Tests 3
