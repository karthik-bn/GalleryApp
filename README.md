GalleryApp Android Application
------------------------------

I have built the Main screen/homescreen using SimpleAdapter. And for 1:1 preview, I used ViewPager and its adapter. The user interface part(the XMLs') is loosely coupled with implementation part(the java class files). Thus, we can expect more flexibility for future updates/modifications.

And below are the list of things I wasn't able to cover.
1. The 1:1 preview with continuous scrolling.    --->   The reason is, I am new to the world of gesture detector. I wish, I had had more time. However, users can able to sroll through the images horizontally to preview them.
2. Loading images into "Assets" folder.   ---> Initially, I tried to load pictures to Assets, and later tried to invoke those images to the listview. But, it was taking more time(I believe, it's because of bitmap decoding) to load the list. So, I had to load all those images to "drawable" folder for quick retrieval.


And, for some reason, the images inside the 'Drawable' folder appears to be mis-rotated. But, the actual images(the one in the physical folder) are completely fine.

