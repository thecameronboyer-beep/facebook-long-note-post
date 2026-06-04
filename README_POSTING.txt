Facebook Post Package

Files:
- index.html: the page people click.
- og-preview.png: the normal Facebook preview image.
- full-note.png: the huge horizontally scrollable notebook image.

How to post:
1. Upload this whole folder to a static host, such as Netlify Drop, Cloudflare Pages, GitHub Pages, or your own site.
2. Copy the final public HTTPS URL for the folder/page.
3. Open index.html and replace every instance of:
   https://YOUR-PUBLIC-URL
   with your real public URL, for example:
   https://example.net/note
4. Re-upload index.html if needed.
5. Paste the final public page URL into Facebook.
6. Use POST_CAPTION.txt as the caption, or write your own.

Important:
- Do not upload full-note.png directly to Facebook if you want the normal preview card.
- Post the page URL. Facebook will show og-preview.png, and the click opens full-note.png in a sideways scroll page.
- If Facebook shows an old preview, use the Facebook Sharing Debugger to scrape the URL again:
  https://developers.facebook.com/tools/debug/

