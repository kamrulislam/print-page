# print-page


```css
@page { counter-increment: page }
@page {
   @bottom-right {
    content: counter(page) " of " counter(pages);
   }
}
```