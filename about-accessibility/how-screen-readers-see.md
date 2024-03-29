# 1.2 How is content perceived?

### Try this experiment

Go to the [_New York Times_ website](https://www.nytimes.com) and ask yourself the following questions. What are you reading to understand the page? Are you reading every word or just the headlines? Looking at the photos? Going to the page navigation? Which methods help you understand the page the easiest and the fastest?

<figure><img src="../.gitbook/assets/Screen Shot 2019-03-11 at 10.05.00 AM.png" alt="Sample homepage of the New York Times"><figcaption></figcaption></figure>

Accordingly to [eye-tracking studies](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/), we initially skim pages for content by scanning page elements such as headlines and key text such as phone numbers. Then we zoom into the sections of text to read the details that interest us.

An aspect taken for granted in this process is that we can do all this because **we can see the site**.

Our senses — such as sight and hearing — are input devices to our brain. We rely heavily on our senses for everything we do online. However, if we cannot rely on one of those senses, everything changes.

### Assistive technology helps shift senses

This is where assistive technology comes into play— it can shift input to a sense you can rely on. For instance, closed captions allow a person to read the dialog and environmental sounds from a video they might not be able to hear. In turn, a person using a screen reader can listen to articles online they cannot see. Indeed, a screen reader can provide in-depth information about page structure, content, and navigation— providing the same information we visually scan.

## Making the web visible to a screen reader

However, screen readers themselves cannot see. They can only communicate page content and structure based on how our pages are encoded and organized. Not encoded properly, content can go missing or its intent lost.

For example, a screen reader relies on headings coded into the page to communicate article headlines or section titles within an article. For example, `<h1>` is for a top level heading, `<h2>` for second level, etc.

With our headline labeled as a heading, our screen reader can indeed see it as a headline.&#x20;

```markup
<h2>Article headline</h2>
<p>This is the first paragraph of content.</p>
```

On the other hand, what if we only make the words bold? The words will stand out visually, but a screen reader has no means of knowing if we intend for this text to be a headline or simply emphasized.

```markup
<p><strong>These words are bold, but is it a headline?</strong></p>
<p>This is the first paragraph of the article.</p>
```

When used correctly, our content management system, such as LibGuides or Wordpress, can handle most of these simple coding needs. However, as we write our content, we can still introduce many errors that can make reading the pages with a screen reader difficult at best. Avoiding these errors is where this guide hopes to help!

## Read more...

* [How People with Disabilities Use the Web](https://www.w3.org/WAI/people-use-web/)
* [I Used The Web For A Day Using A Screen Reader](https://www.smashingmagazine.com/2018/12/voiceover-screen-reader-web-apps/)
