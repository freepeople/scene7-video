# Scene7 Video

## <a name="linkVideo">Linking a video URL to a mobile site or a website</a>

After you publish a video, you can obtain its URL for use in your website, mobile site, or desktop application. Use the video URL when you
want to display video in a pop-up or modal window on top of the web page.

When a customer clicks the link, their device, bandwidth, and screen size are automatically detected. The appropriate video is displayed for
playback in a pre-defined viewer for desktop, or in the mobile device's native video player for smartphones and tablets.

See also [Embedding](#embedVideo) the video viewer on a web page.

### To link a video URL to a mobile site or a website

1. In the Asset Browse panel, in the Show drop-down list, click Video or Adaptive Video Set.

2. In the Asset Library panel on the left side, navigate to the asset folder that contains the video or adaptive video set you want to link.

3. Above the Asset Browse panel, on the right side of the toolbar, do one of the following:

    * Click Grid View or List View. In the Asset Browse panel, double-click the video thumbnail of a single asset to open it in Detail View. In
    the URLs and Embed Code panel on the right, under HTTP Streaming, click Copy URL to the right of the viewer you want. As a best practice, copy
    the URL associated with the Universal_HTML5_Video viewer.

    * Click Grid View. In the Asset Browse panel, select a single asset, and then below the thumbnail image, click Preview > Viewer List. In the
    Viewer List page, under the Actions column of the table, click Copy URL. As a best practice, copy the URL associated with the
    Universal_HTML5_Video viewer.

    * Click List View. In the Asset Browse panel, select a single asset, and then to the right of the thumbnail image, click Preview > Viewer List. In
    the Viewer List page, under the Actions column of the table, click Copy URL. As a best practice, copy the URL associated with the Universal_HTML5_Video viewer.

    * Click Grid View, List View, or Detail View. On the same toolbar, click Preview > Viewer List. In the Viewer List page, under the Actions
    column of the table, click Copy URL. As a best practice, copy the URL associated with the Universal_HTML5_Video viewer.

4. Paste the HTML5 video URL link on your website and mobile site.

## Embedding the video viewer on a web page

Use the Embed Code feature when you want to play the video embedded on the web page. You copy the embed code to the clipboard so you can paste it
in your web pages. Editing of the code is not permitted in the Embed Code dialog box.

See also [Linking](#linkingVideo) a video URL to a mobile site or a website.

### <a name="embedVideo">To embed the video viewer on a web page</a>

1. In the Asset Browse panel, in the Show drop-down list, click Video or Adaptive Video Set.

2. In the Asset Library panel on the left side, navigate to the asset folder that contains the video or adaptive video set whose embed code you want to copy.

3. Above the Asset Browse panel, on the right side of the toolbar, do one of the following:

    * Click Grid View or List View. In the Asset Browse panel, double-click the video thumbnail of a single asset to open it in Detail View. In the
    URLs and Embed Code panel on the right, under HTTP Streaming, click Embed Code to the right of the viewer you want. As a best practice, click
    Embed Code that is associated with the Universal_HTML5_Video viewer.

    * Click Grid View. In the Asset Browse panel, select a single asset, and then below the video thumbnail image, click Preview > Viewer List. In
    the Viewer List page, under the Actions column of the table, click Embed Code. As a best practice, click Embed Code that is associated with
    the Universal_HTML5_Video viewer.

    * Click List View. In the Asset Browse panel, select a single asset, and then to the right of the thumbnail image, click Preview > Viewer List. In
    the Viewer List page, under the Actions column of the table, click Embed Code. As a best practice, click Embed Code that is associated with the Universal_HTML5_Video viewer.

    * Click Grid View, List View, or Detail View. On the same toolbar, click Preview > Viewer List. In the Viewer List page, under the Actions
    column of the table, click Embed Code. As a best practice, click Embed Code that is associated with the Universal_HTML5_Video viewer.

4. In the Embed Code dialog box, click Copy to Clipboard. Editing the code is not permitted in the Embed Code dialog box.

5. Click Close.

6. Paste the embed code in your web pages.

### Implementing embed code for using HTML5 video with MP4 and OGG video assets

If you do not use the Scene7 HTML5 video player, but instead want to use the native HTML5 <video> tag with MP4 and OGG video assets, you can use the following embed code sample:
````
    <video poster="S7 video thumbnail URL" controls>
        <source src="S7 OGG video asset URL (no player)" type='video/ogg; codecs="theora, vorbis"'/>
        <source src="S7 MP4 mobile progressive video asset URL (no player)" type='video/mp4; codecs="avc1.4D401E, mp4a.40.2"'/>
        <p>This is fallback content</p>
    </video>
````
* Replace "S7 video thumbnail URL" with the video's thumbnail URL. This is the video’s thumbnail image that a user sees before they play the video.

* See Obtaining video thumbnail URLs.

* Replace "S7 OGG video asset URL (no player)" with the video’s progressive URL for OGG video. See [Linking](#linkingVideo) a video URL to a mobile site or a website.

* Replace "S7 MP4 mobile progressive video asset URL (no player)" with the video’s mobile progressive URL. See [Linking](#linkingVideo) a video URL to a mobile site or a website.
