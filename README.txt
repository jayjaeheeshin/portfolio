Jaehee Shin — Portfolio (static export)

index.html       the whole site, self-contained (fonts, images, styles inlined)

cover.html       -> index.html#cover
contents.html    -> index.html#index      (the index / table of contents)
print.html       -> index.html#print
video.html       -> index.html#video
campaign.html    -> index.html#campaign
branding.html    -> index.html#branding
about.html       -> index.html#about

video/           MP4 assets. Keep this folder next to index.html.

Every page is directly linkable via its hash URL, e.g.
  yourdomain.com/index.html#video

Note on images: pictures dropped into the design are stored in the
browser of the machine where they were placed. To publish them,
replace each <image-slot> with <img src="..."> pointing at a real file.
