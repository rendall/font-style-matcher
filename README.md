# font-style-matcher

If you're using a web font, you're bound to see a flash of unstyled text (or FOUC),
between the initial render of your websafe font and the webfont that you've chosen.

This usually results in a jarring shift in layout, due to
sizing discrepancies between the two fonts. To minimize this
discrepancy, you can try to match the fallback font and the intended webfont’s
x-heights and widths [[1]](http://helenvholmes.com/writing/type-is-your-right).


This tool helps you do _exactly_ that.

![fouc](https://cloud.githubusercontent.com/assets/1369170/20506300/ed61ebac-b007-11e6-8324-df0a90604acd.gif)

## fork

This is a fork of [@notwaldorf](https://github.com/notwaldorf/font-style-matcher)'s
excellent [font-style-matcher](https://github.com/notwaldorf/font-style-matcher).
This fork makes minor adjustments to the layout, removes the instructions, changes
the font unit from *px* to *rem*, and changes the default fonts, solely for my own
convenience.

## url

You might find it useful! The altered layout is at [https://rendall.github.io/font-style-matcher/](https://rendall.github.io/font-style-matcher/)
