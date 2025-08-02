# Syntax

## Links

### Obsidian wiki-links

Note: Flowershow is configured to work with Obsidian shortest-path-possible wiki-links, but will also work with Obsidian absolute paths.

<div data-testid="obsidian-wiki-link">
[[post-1]]
</div>

<div data-testid="obsidian-wiki-link-absolute">
[[blog/post-1]]
</div>

<div data-testid="obsidian-wiki-link-relative">
[[../blog/post-1]]
</div>

<div data-testid="obsidian-wiki-link-short-readme">
[[README]]
</div>

<div data-testid="obsidian-wiki-link-short-readme-2">
[[blog/README]]
</div>

<div data-testid="obsidian-wiki-link-relative-readme">
[[../README]]
</div>

<div data-testid="obsidian-wiki-link-special-signs">
[[Post With Special Chars %&(1)+]]
</div>


### Obsidian embeds

<div data-testid="obsidian-embeds">

`![[image.jpg]]`
![[image.jpg]] 

`![[../assets/image.jpg]]`
![[../assets/image.jpg]]

`![[/assets/image.jpg]]`
![[/assets/image.jpg]]

</div>

### CommonMark links

<div data-testid="common-mark-links">

[post-1](post-1.md)

[./post-1](./post-1.md)

[/blog/post-1](/blog/post-1.md)

[/README](/README.md)

[../README](../README.md)

[External link](https://example.com)

</div>

### CommonMark embeds

<div data-testid="common-mark-embeds">

`![../assets/image.jpg](../assets/image.jpg)`
![../assets/image.jpg](../assets/image.jpg)

`![/assets/image.jpg](/assets/image.jpg)`
![/assets/image.jpg](/assets/image.jpg)

</div>

## JSX blocks

<div data-testid="jsx-img">
  <img alt="Image" src="assets/image.jpg"/>
</div>
