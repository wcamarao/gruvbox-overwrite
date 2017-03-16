# Gruvbox Overwrite

This is an extension to the awesome [gruvbox-plus-syntax](https://atom.io/themes/gruvbox-plus-syntax) Atom theme to make the syntax highlighting simpler by reducing the variety of colors. The original theme supports several languages and it's up to date with latest Atom (1.15) which [removed shadow DOM boundaries](http://blog.atom.io/2016/11/14/removing-shadow-dom-boundary-from-text-editor-elements.html). However, the color scheme is too variant meaning functions differ from methods and so on. Instead, I prefer to emphasize punctuation and keywords while treating callables equally.

## Preview

![Preview](/preview.png)

## Setup

##### 1. Install [gruvbox-plus-syntax](https://atom.io/themes/gruvbox-plus-syntax)

##### 2. Create a symlink:

```
$ ln -s <path/to>/overwrite.less ~/.atom/packages/gruvbox-plus-syntax/styles/overwrite.less
```

##### 3. Edit `index.less` and add:

```css
@import 'styles/overwrite';
```

##### 4. Edit `styles/schemes/dark-{contrast}.less` and change:

```css
@foreground: #D2B48C;
```

##### 5. Edit `styles/schemes/dark.less` and change:

```css
@blue: #4682B4;
@purple: #BA55D3;
```

## Credits

### MIT License

Thanks to [Pavel Pertsev](https://github.com/morhetz) for the original gruvbox for vim, and to [Brian Reilly](https://github.com/Briles) for the Atom version.
