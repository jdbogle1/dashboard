1. On Ex1.2, I first researched changing the size of the resize handle
2. I learned `::-webkit-resizer {}`
3. I wrote code such as: 
```css
::-webkit-resizer{
    border: solid;
    height: 100%;
}
```

> The first issue with this is that it is only functional on certain compatible browsers.
> There also seems to be limited use of this pseudo selector, setting a new height didn't actually change anything.
