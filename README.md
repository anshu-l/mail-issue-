# mail-issue-
Option B — Host the images online and use absolute URLs (best if you reuse the template)

Upload each image to a hosting service that provides a direct image URL (Imgur, GitHub repo raw files, your website, or an image host).

Example easy hosts: Imgur (image page → right-click → “Open image in new tab” → copy URL), GitHub (upload to repo → use raw file link).

In your HTML replace src="main.png" with the full URL, e.g.

<img src="https://i.imgur.com/yourimage.png" alt="IEEE Day" />


Open the updated HTML in a browser to confirm. Copy the rendered page → paste into Gmail or use the developer-console HTML insertion method.

Note: Some recipients may have image blocking settings; hosting lets Gmail cache the images and generally works well.
