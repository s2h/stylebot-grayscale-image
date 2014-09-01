stylebot-grayscale-image
========================

just use Stylebot addon for your browser and this code:
```css
.article_content img {
    -webkit-filter: grayscale(0.8);
    filter: grayscale(0.8);
    opacity: 0.6;
}

.article_content img:hover {
    -webkit-filter: grayscale(0);
    filter: grayscale(0);
    opacity: 1;
}
```
use your class instead of *.article_content*
