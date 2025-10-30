# Syntax (MD rendering)

## Links

### Obsidian wiki-links

Note: Flowershow is configured to work with Obsidian shortest-path-possible wiki-links, but will also work with Obsidian absolute paths.

[[post-1]]

[[blog/post-1]]

[[../blog/post-1]]

[[README]]

[[blog/README]]

[[../README]]

[[Post With Special Chars %&(1)]]

### Obsidian embeds

![[image.jpg]] 

![[assets/image.jpg]] 

❌ This won't work atm
![[../assets/image.jpg]]

![[Image With Special Chars %&(1).jpg]] 

### CommonMark links

[post-1](post-1.md)

[./post-1](./post-1.md)

[/blog/post-1](/blog/post-1.md)

[/README](/README.md)

[../README](../README.md)

[External link](https://example.com)

### CommonMark embeds

`![../assets/image.jpg](../assets/image.jpg)`
![../assets/image.jpg](../assets/image.jpg)

`![/assets/image.jpg](/assets/image.jpg)`
![/assets/image.jpg](/assets/image.jpg)

## Problematic characters

This sentence includes special MDX signs: 50 < 100 <100 <= 100 => 100> 100 > 50

## HTML blocks

```
<span style="color: tomato; font-weight: bold;">This text is red and bold.</span>
```

<span style="color: tomato; font-weight: bold;">This text is red and bold.</span>

