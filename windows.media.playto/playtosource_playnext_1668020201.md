---
-api-id: M:Windows.Media.PlayTo.PlayToSource.PlayNext
-api-type: winrt method
---

<!-- Method syntax
public void PlayNext()
-->

# Windows.Media.PlayTo.PlayToSource.PlayNext

## -description
Connects the next Play To source element to the Play To target.

## -remarks
You can use the [PlayNext](playtosource_playnext.md) method to stop streaming the current Play To source media to the target and then start streaming the Play To source identified by the [Next](playtosource_next.md) property to the Play To target.

For an example of using the [Next](playtosource_next.md) property, see [Streaming a slide show using Play To
(JavaScript)](http://msdn.microsoft.com/library/780cb5f5-4ee5-4294-ad60-5be54107838a) or [Media casting](http://msdn.microsoft.com/library/40b97e0c-eb1b-40c2-a022-1ab95dfb085e).

## -examples


[!code-csharp[SlideShow](../windows.media.playto/code/PlayTo_SlideShow1/csharp/MainPage.xaml.cs#SnippetSlideShow_CS)]

[!code-js[SlideShow](../windows.media.playto/code/PlayTo_SlideShow1/javascript/default.js#SnippetSlideShow)]

[!code-vb[SlideShow](../windows.media.playto/code/PlayTo_SlideShow1/vbnet/MainPage.xaml.vb#SnippetSlideShow_CS)]

## -see-also
[Play To sample](http://go.microsoft.com/fwlink/p/?linkid=245166), [PlayToReceiver sample](http://go.microsoft.com/fwlink/p/?linkid=245167), [Media Server sample](http://go.microsoft.com/fwlink/p/?linkid=245168)
