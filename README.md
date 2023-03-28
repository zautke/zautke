<!-- 2.6.7 -->

<svg fill="none" width="100%"  xmlns="http://www.w3.org/2000/svg">
 <foreignObject width="100%" height="100%">
  <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .wrapper {
          height: 100vh;
          display: grid;
          place-items: center;
        }

        .text {
          width: 9ch;
          animation: typing 1.5s steps(9), blink .5s step-end infinite alternate;
          white-space: nowrap;
          overflow: hidden;
          border-right: 3px solid;
          font-family: monospace;
          font-size: 4em;
          background: linear-gradient(90deg, rgba(0,241,220,1) 0%, rgba(86,115,241,1) 44%, rgba(103,68,241,1) 54%, rgba(254,0,255,1) 100%);
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
        }

        @keyframes typing {
          from {
            width: 0
          }
        }

        @keyframes blink {
          from, to { border-color: transparent }
          50% { border-color: rgba(254,0,255,1); }
        }
      </style>
      <div class="wrapper">
        <div class="text">
          CodeFlow.
        </div>
      </div>
  </div>
 </foreignObject>
</svg>

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

