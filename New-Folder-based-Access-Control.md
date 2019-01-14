Emby 4.0 includes a new way to do Merged Libraries that is very powerful.  If you were using merged libraries in a previous version of Emby you will want to redo your setup to take advantage of this new way to accomplish the same thing.  The previous method was a user preference to combine different libraries of liked content.  Now with version 4.0 this is all handled in the library access control making it much easier to manage.

To get an idea of what merged libraries are and how to effectively use them let’s take an example where you have multiple types of TV Show content broken up and stored on disk by categories. Below is the category of TV Show and the physical location to the parent directory of each.

* Anime – G:\TV Shows\Anime
* Reality TV – G:\TV Shows\Reality TV
* Cartoons – H:\TV Shows\Cartoons
* Talk Shows - H:\TV Shows\Talk Shows
* Sporting Events – I:\TV Shows\Sporting Events
* News – I:\TV Shows\News
* Kids Shows – J:\TV Shows\Kids Shows
* Shows – J:\TV Shows\Shows

What we are going to do is create ONE library called “TV Shows” that contains these 7 folders.  We’ll do this the normal way by selecting LIBRARY from the administration web panel. We should then be presented with the following:

![Library](https://emby.media/resources/Library.png)

Select "Add Media Library" to get to this:

![Library](https://emby.media/resources/Library2.png)

We will now select the content type from the drop down menu of “TV Shows” and we will also use the default library name of “TV Shows”. You can change this name to anything you want.

![Library](https://emby.media/resources/Library3.png)

Now the last thing we need to do to have a working “TV Show” library is to add each of the parent folder mount points shown above for this example. We do this by clicking on the + (plus sign) next to the word “Folders” above.  Once we have added each of these parent folders this section will look like this:

![Library](https://emby.media/resources/Library4.png)
