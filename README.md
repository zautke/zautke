<!-- 2.6.7 -->

<style>
h1 {
  font-size: 24pt
  color: purple;
  animation: myanimation 2s infinite;
}

@keyframes myanimation {
  from {
    color: purple;
  }
  to {
    color: blue;
  }
}
</style>

<h1>LUKE</h1>

<div align="center">
    <img src="test.svg" width="400" height="400" alt="saluation">
</div>

> [!NOTE]
> Thing to mention

> [!CAUTION]
> Contents may be hot!

# Using CSS in Readme.md file

Readme.md files do not allow direct CSS classes injection.

Though, there are several ways you can inject a CSS file or link into your README.md file, I prefer using the SVG files for simple styling or even complex charts and tables. [see my simple `Readme.md` example with SVG styling][1]

## ![plot](./title.svg)

This is a title that can be manipulated.

## ![plot](./subTitle.svg)

This is a sub-title with cyan color but can be manipulated

