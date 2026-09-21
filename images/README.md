# Put your images here

- `profile.jpg` appears on the home page. It is currently a sample flower photo.
- `travel.jpg` appears on the travel page. It is currently a sample Niagara Falls photo.

To replace one: put your own photo here with the same filename, or change the path in the page to match your new filename. A file named `profile.png` will not match a link to `profile.jpg`.

Use short lowercase names with hyphens, such as `campus-walk.jpg`. Use JPG, PNG, WebP, or SVG. If your phone exports HEIC, export a JPG or PNG first. Smaller photos load faster; around 1600 pixels on the long edge is plenty for most pages.

In a main page:

```markdown
![](images/campus-walk.jpg){fig-alt="A useful description of the image"}
```

In a blog post, go up one folder first:

```markdown
![](../images/campus-walk.jpg){fig-alt="A useful description of the image"}
```

The words in `fig-alt` are alternative text for readers who cannot see the photo. A caption is optional: put it between the empty `[]` brackets to show it beneath the photo. Replace both the photo and its description. Use photos you have permission to publish.
