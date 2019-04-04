# 2.3 Video and Audio

## The Interaction

{% hint style="info" %}
Multimedia can be a massive roadblock as it is inherently an audio/visual experience. This can leave students who have difficulty perceiving one or the other without access to the content.
{% endhint %}

## Solutions: Transcripts and closed captioning

We must proactively create multimedia in an accessible manner by including both transcripts and closed captioning. Having both may seem redundant, but each fulfills different needs. For example, a video with flashing content can cause serious issues for people who suffer from epilepsy or migraines. The transcript becomes the tool that provides the content for this video.

### Externally-created multimedia

The captioning and transcript requirements also apply to video from outside sources. Older videos which do not include captioning can cause issues. As such, many colleges/universities have offices which create provide captioning and transcripts. Bring these folks donuts as they do solid work for our students.

If a professor wants to use library videos which lack captioning, we have a choice of creating captioning or suggesting alternative resources. Everyone must be able to access course material content.

## Additional Tips and Notes

* The link to the transcript should be easily identifiable and adjacent to the video. 
* Keep locally created video tutorials short and to the point.
* Closed captions should reflect all sound that conveys content. This includes all relevant background noises and sound effects.
* Ideally, student should be able to control the close captioning during playback such as captioning color and size.

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

Helper tools are not as helpful for multimedia as the captions or transcripts are often embedded from off-site. Thus, manually check each of your videos or audio clips for these content aid features.

## Additional information

[Multimedia accessibility FAQ](https://www.w3.org/2008/06/video-notes)

