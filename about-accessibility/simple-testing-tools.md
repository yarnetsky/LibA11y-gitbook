# 1.4 Simple accessibility testing tools

In the next section, strategies will be outlined for creating accessible content. But first, let's install a simple tool that can double check your work as it is created. 

## Install Tota11y, an accessibility visualization tool

The [**Tota11y**](http://khan.github.io/tota11y/) javascript bookmarklet was created by the Kahn Academy to visualize how web content is perceived by screen readers and other assistive technology. 

### Install option 1: bookmarklet <a id="Installation"></a>

Is your bookmarks bar visible in your browser? If so, try this option. To install, click and hold the Tota11y link in the box below, then drag the link from the box into your bookmarks bar. To activate the tool, simply click the bookmark.

{% hint style="info" %}
\*\*\*\*[**Tota11y**](javascript:%28function%28%29{var%20tota11y=document.createElement%28'SCRIPT'%29;tota11y.type='text/javascript';tota11y.src='https://khan.github.io/tota11y/tota11y/build/tota11y.min.js';document.getElementsByTagName%28'head'%29[0].appendChild%28tota11y%29;}%29%28%29;)\*\*\*\*
{% endhint %}

### Install option 2: Chrome or Firefox extension

This same tool has also been adapted to be a Chrome and Firefox extension. Install the extension and you'll see the eyeglasses icon in your toolbar, which you can click to activate.

* [Tota11y Chrome extension](https://chrome.google.com/webstore/detail/tota11y-plugin-from-khan/oedofneiplgibimfkccchnimiadcmhpe/related)
* [Opena11y Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/opena11y-toolkit/): Using the Tota11y script.

## Using Tota11y

![Click the glasses icon at the bottom corner to activate](../.gitbook/assets/screen-shot-2019-03-21-at-2.19.09-pm.png)

1. Go to the page you wish to evaluate
2. Click the Tota11y bookmark you just installed \(or the Chrome extension icon\).
3. A black x-ray glasses icon will appear at the bottom left corner of your page \(screenshot above\).
4. Clicking the glasses, you'll see a pop-up menu with choices such as Headers, Contrast, and Image alt-text.
5. Clicking one of these options will provide information and screen annotations and track any errors.
6. Dismissing the tools
   * Clicking the option a second time dismisses the report.
   * Similarly clicking the glasses again minimizes the tool.

This YouTube video shows this process in motion.

{% embed url="https://www.youtube.com/embed/78fhYurzlYc" %}

We will review many of Tota11y's tools in the following pages as we talk about how to create better content.

## Additional easy to use testing tools

* **WAVE Accessibility Evaluation Tools**
  * [Website version](http://wave.webaim.org/)
  * [Chrome extension](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
  * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/wave-accessibility-tool/)
* [ANDI - Accessibility Testing Tool](https://www.ssa.gov/accessibility/andi/help/install.html)
  * bookmarklet with multiple testing tools
* **Contrast checkers**
  * [Color Contrast Checker](https://webaim.org/resources/contrastchecker/)
  * [Color-reliant Link Contrast Checker](https://webaim.org/resources/linkcontrastchecker/)
* **Color blindness visualization tools**

  * [Spectrum \(Chrome extension\)](https://chrome.google.com/webstore/detail/spectrum/ofclemegkcmilinpcimpjkfhjfgmhieb?hl=en)
  * [NoCoffee vision simulator \(Chrome extension\)](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl?hl=en-US)

