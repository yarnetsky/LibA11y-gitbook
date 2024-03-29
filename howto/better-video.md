# 2.6 Video and Audio

## Screen Reader Interaction

{% hint style="info" %}
Without alternative access to the content, audio and visual media can leave users who have visual or auditory impairments without access to the content.
{% endhint %}

## Solutions: Transcripts and closed captioning

Content creators must proactively create multimedia in an accessible manner by including both transcripts and closed captioning. Having both may seem redundant, but each fulfills different needs. For example, a video with flashing content can cause serious issues for people who suffer from epilepsy or migraines. The transcript becomes the tool that provides the content for this video.

### Audio Description

Some video projects will also need audio description. This is a supplemental audio track that describes the visual elements of the video if the primary soundtrack does **not** convey the content through spoken word.&#x20;

### Externally-created multimedia

These requirements also apply to video not created by the library— this is especially important at academic/K12 libraries. If a professor wants to use a library video for their students that lack these descriptive tools, such as an old VCR tape, we have a choice— we can either create the descriptive tools or suggest alternative resources. This is a common occurrence. As such, many colleges/universities have offices which create captioning and transcripts. The bottom line is that all students enrolled in a course must be able to access course material and should be able to do so at the same time.

## Additional tips

* The link to the transcript should be easily identifiable and adjacent to the video.&#x20;
* Keep locally created video tutorials short and to the point.
* Closed captions should reflect all sound that conveys content. This includes all relevant background noises and sound effects.
* Ideally, users should be able to control the close captioning during playback such as captioning color and size.
* Do not use video that automatically plays when the webpage loads.

### **Sample video transcript button**

If a transcript overloads your page with information, you can use the following code to create a show/hide transcript button. This button taps into the Bootstrap framework packaged with LibGuides so additional javascript is not required.

```markup
<p><a aria-controls="collapse-transcript" aria-expanded="false" class="btn btn-primary btn-sm" 
data-toggle="collapse" href="#collapse-transcript">Video Transcript</a></p>
    <div class="collapse" id="collapse-transcript"> 
    <div class="card card-block"> TRANSCRIPT HERE
    </div>
 </div>
```

* From: [Bootstrap Collapse functionality](http://getbootstrap.com/javascript/#collapse)

## Testing

Accessibility testing tools are not as helpful for multimedia as the captions or transcripts are often embedded from off-site. Thus, manually check each of your videos or audio clips for these content aid features.

## Read more...

* [Multimedia accessibility FAQ](https://www.w3.org/2008/06/video-notes)
