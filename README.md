[![Jane Ori - PropJockey.io](https://img.shields.io/badge/Jane%20Ori%20%F0%9F%91%BD-%F0%9F%A4%8D%20PropJockey.io-7300E6.svg?labelColor=FB04C2&style=plastic)](http://jane.propjockey.io/)

# propjockey-brand
PropJockey pngs, svgs, favicons, and more

README shields.io Badge:

```
[![Jane Ori - PropJockey.io](https://img.shields.io/badge/Jane%20Ori%20%F0%9F%91%BD-%F0%9F%A4%8D%20PropJockey.io-7300E6.svg?labelColor=FB04C2&style=plastic)](http://jane.propjockey.io/)
```

## PropJockey

### tag line
"the value of properties, orchestrated"

### Colors

Hex:

- Brand1 (Purple) `#8100f0`
- Brand2 (Pink) `#ff00c7`
- BrandBlend (Face) `#b989c0`

HSL:

- Brand1 (Purple) `hsl(todo)`
- Brand2 (Pink) `hsl(todo)`
- BrandBlend (Face) `hsl(todo)`

LCH:

- Brand1 (Purple) `lch(todo)`
- Brand2 (Pink) `lch(todo)`
- BrandBlend (Face) `lch(todo)`

### Static Logo PNGs

| Standard | Lines | Lines-White |
| --- | --- | --- |
| ![propjockey](https://github.com/propjockey/propjockey-brand/assets/7545075/f003ff3c-8b31-4823-ac37-703307a98c94) | ![propjockey-lines](https://github.com/propjockey/propjockey-brand/assets/7545075/500d0451-4bb2-4547-a126-5f875cc8bb26) | ![propjockey-lines-white](https://github.com/propjockey/propjockey-brand/assets/7545075/1bbd1310-3d92-421b-8720-823b66ca8aad) |

## Embeded SVG var() Enhancements

If embeded, `propjockey.svg` has the following CSS var() enhanced functionality and fallback defaults

- `var(--pjLogoBrand1, #8100f0)`
- `var(--pjLogoBrand2, #ff00c7)`
- `var(--pjLogoFace, #b989c0)`
- `var(--pjLogoEyes, #ffffff)`
- `var(--pjLogoColorOpacity, 1)`
- `var(--pjLogoLines, currentColor)`

So if the svg or any ancestor in dom provides those var values, the SVG will use those colors.

The opcity of all the colors (as a group) can be set to 0 so only the lines are shown

Similarly, `propjockey-lines.svg` has this var enhancement:

`var(--pjLogoLines, currentColor)`

So, if embeded, it will automatically use the containing element's current font color.

The var overwrites it for consistency.

Further, `propjockey-lines-white.svg` has this var enhancement:

`var(--pjLogoLines, #ffffff)`

So it defaults to white but can be overwritten with the common var should it exist.

---

## Other PropJockey brands

### augmented-ui

Specifically all lowercase and with a dash "augmented-ui" (avoid "Augmented UI" etc)

todo: many other projects here

---

## PS:

These sites/services are just the best:

https://shields.io/badges

https://realfavicongenerator.net/

https://svgtrace.com/png-to-svg

https://svgomg.net/

Much appreciation <3
