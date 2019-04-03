# Images

## The Interaction

{% hint style="info" %}
Students using a screen reader will hear the alternative text read aloud when encountering an image on your page. Lacking this text, the content will become invisible to the reader.
{% endhint %}

## Solution: Use Alternative Text to describe your images

Screen readers will read this "alt text" in the place of your image to convey the intended meaning. 

### What should be included in the alt text?

* All _relevant_ information about the image’s appearance and function.
* Keep it brief.
* You can skip introductory phrases such as "image of...." as the screen reader will announce it is an image by default.

### Alt text is not needed when...

* Graphics are purely decorative.
* Alt text would be repetitive information.
  * For example, the alt text for a book cover might be its title. If the image is next to a catalog link that also features the title, the alt text become redundant.
* In these cases still use, we still need an alt tag, but it would be empty— &lt;img src="http://.../images/decorative.jpg" alt="" /&gt;

### How to add alt-text in LibGuides

The image properties tool in LibGuides \(below\) provides a space where we can easily insert this description as you insert or edit the image. WordPress and other CMS have similar dialog boxes where you can enter the alt text.

![In LibGuides, entering alternative text is easy as you insert or edit your image.](../.gitbook/assets/alt-statement.jpg)

## Testing

* Click "Image alt-text" in Tota11y.
* The error window will report if there are any images requiring alt text.
* Next to the error message you'll see a small magnifying glass. You can click this icon to see which image caused the error.
* Accessibility testing requires human verification. 
  * For example, a missing alt-text can be reported for decorative images. If the image is indeed decorative or redundant info, don't worry about the error.

## Additional information

For best practices on creating alternative text, please consult the links below.

* [WebAIM Alternative Text Guide](http://webaim.org/techniques/alttext/)
* [Image ALT Tag Tips from Penn State](http://accessibility.psu.edu/images): Gives helpful examples of Alt Text descriptions for different situations.

