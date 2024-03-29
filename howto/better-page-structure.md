# 2.1 Page Structure

Good page structure is the crucial first step. The key here is to use your content management system's built-in content structure tools in a logical manner.&#x20;

## Screen reader interaction

{% hint style="info" %}
* When first landing on a web page, the screen reader announces the page title.
* Users can quickly skim the contents of a webpage by listening to the page headings. This helps a user understand a page's content structure and hierarchy.
* Headings also act as page navigation. A person using a screen reader, having listened to the page's headings, can then jump to any heading on a page.&#x20;
* The screen reader announces the presence of an ordered and unordered lists and the number of items in the lists before reading the individual items.
* Content is described in a linear fashion by the screen reader. As such, even three-column pages are described as a single column starting with the first column.
{% endhint %}

## Solutions&#x20;

### Create page titles that are brief, but meaningfully describe of your page content

Titles are critical. Not only are they announced by screen readers, they also appear in browser tabs and search results. It's best to include the page information before section or site information. For instance, the title of this page is: "Page Structure - LibA11y: Making our library content accessible."

### Use headings to give your content a logical hierarchy.&#x20;

Use page headings to outline content— not unlike a bulleted page outline or table of contents. Use the headings in order and don't skip headings.

In LibGuides, for instance, Heading 1 `<h1>` is reserved for guide titles and Heading 2 `<h2>` is held for box titles. For content within the boxes, use headings 3 to 6. Here's an example of how to use headings to keep content in order.

{% hint style="info" %}
* **H1 Guide Title**
  * **H2 Box Title**
    * H3 Section inside a box
      * H4 Sub-section
      * H4 Sub-section
    * H3 Section inside a box
  * **H2 Box Title**
    * H3 Section
    * H3 Section
      * H4 sub-section
      * H4 sub-section
{% endhint %}

### Additional best practices for headings

* Don't use a font-size change alone to signify headings. This heading would be missed by a screen reader.
* Similarly, don't change the headings to simply make text larger or smaller. This can alter your page outline and make it difficult to understand.
* If you need to change the heading's font size, do so after making it a heading.
* Better than using the font size menu, customizing your CSS can resize headings across your entire website.

### How to use headings in LibGuides

1. Click in the paragraph you want to be a header
2. Select the level of heading from the paragraph format menu (pictured below).&#x20;

![In LibGuides, you can create headings from the rich text editor's format drop-down menu](<../.gitbook/assets/Screen Shot 2019-03-18 at 10.54.14 AM.png>)

### Additional page structure tips

* **Use the built-in tools for ordered (numbered) and unordered (bulleted) lists.** When creating lists, think about the type of list needed. For instance, if the list is a series of steps, use the ordered list tool. If order is not critical then using the bulleted list tool works perfectly.
* **With multi-column pages, watch your content order closely.** Because the entire first column will be read before the second column, don't place related materials side-by-side in different columns if there is unrelated material below in the first column.

## Testing

### Using WAVE tool

* Clicking your WAVE tool extension icon for the testing side panel to appear. Click on the Structure tab to see the headings report.
* Scroll through the list to see if any error or warning icons appear noting that either heading levels are out of order are that levels are being skipped. You will also see these warning icons appear on your web page.
* For instance, in the screenshot below, the headings of this page are skipping from h1 to h3. The order should be h1 to h2. &#x20;
* Read through your order to ensure your headings and nesting order make sense as an outline of the page.
* Also, click the Order tab to view the order your content will be read by a screen reader. This is the same the order that people who use keyboards for navigation will scroll through your page.

<figure><img src="../.gitbook/assets/Screenshot 2024-03-28 at 11.50.27 AM.png" alt="" width="274"><figcaption><p>This structure report shows this page is skipping a heading level.</p></figcaption></figure>

### Fix a mistagged heading

Just as you click in a paragraph and change it to a heading from the format menu, you can also repair headings in the same manner. Simply click the heading and select the proper level from the menu.

In rare instances, you'll find a heading accidentally tagged a subsequent paragraph. You can reset the non-heading to "normal" with the same menu.

### **Test your page on a mobile device!**

Another way to visualize the organization of your page is to view it with a phone browser. Your content will become linear in much the same way it does on a screen reader. If the page does not make sense on a phone, a re-ordering of content will be needed.

