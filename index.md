# This is a heading

## Here's a smaller heading

This is a paragraph

* Here's a bulleted list
* Another item

1. And an ordered list
1. The numbers don't matter

> This is a qoute

[This is a link to Google](https://google.com)

```{r}
# Source: http://www.htmlwidgets.org/showcase_plotly.html
library(plotly)
p <- ggplot(data = diamonds, aes(x = cut, fill = clarity)) +
            geom_bar(position = "dodge")
ggplotly(p)
```
