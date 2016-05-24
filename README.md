# Leap Link
Leap Link is an internal page jump that allows you to move quickly inside of a long page.

### Usage—
1.&nbsp;Include a hashtag followed by a reference name to the href attribute of an anchor link element that will trigger the leap.
```
<a href="#leaplink">Leap Link<∕a>
```
2.&nbsp;If you’re leaping to another page, simply include the hashtag followed by the reference name to the end of the page url in the anchor element.
```
<a href="page.html?utm_source=link&utm_medium=email#leaplink">Leap Link<∕a>
```
3.&nbsp;Have URLs that include UTMs for analytics? No problem! All you need to do is append the hashtag & reference name to the very end of the UTM string.
```
<a href="page.html#leaplink">Leap Link<∕a>
```
4.&nbsp;To make it all work; provide an id (#) attribute with the corresponding reference name to the element that the link will need to leap to. This is the same for internal && external leaping.
```
<div id="leaplink">Leap Link Section<∕div>
```


