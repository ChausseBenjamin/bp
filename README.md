Ben's Photostream (BP)
======================
Minimal static photo-gallery generator.

Photo galleries on the web are quite bloated. They use more javascript than
they would need to accomplish something extremely simple: display images.  BP
is a simple shell script which generates a static webpage displaying a photo
gallery using a given folder. Photos are displayed in a relatively
chronological order from the date of the images creation.

Usage:
------

+ Set the `photodir` variable to the folder where your photos are stored. All
photos should be at the root of this folder as BP doesn't search for images
recursively.

+ Set the `galleryfile` variable to the html file in which you want the gallery
to appear.

+ Make sure your `galleryfile` has the following lines somewhere (not having
them will lead to this file being erased):

```
<!-- GB -->

<!-- GE -->
```

+ For insight into how the css styling should be configured, please consult the
included `index.html` file
