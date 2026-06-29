# Customizing the "Made with Podium" watermark

There is a default watermark that reads "Made with Podium" included on the lower-right of each slide in a slide deck rendered using Podium. If you want to customize the text of this watermark to be your GitHub ID, your social media handle, or any other text you choose, you will need to update the `style.css` stylesheet to override the default behavior.

/// note | Note

The `style.css` file included with the example Podium slide bundle ships with the CSS necessary to customize the watermark.

///

To customize the watermark, start with the following in `style.css`:

```css
.remark-slides-area .remark-slide-content::after {
    content: "Made with Podium";
    font-family: 'Droid Serif';
    font-weight: normal;
    font-size: 18pt;
    position: absolute;
    bottom: 12px;
    right: 20px;
    opacity: 0.5;
}
```

The main thing you are likely to want to change is the `content` line. This determines the text that is displayed.

You can update the rest of this block in any way you like.
