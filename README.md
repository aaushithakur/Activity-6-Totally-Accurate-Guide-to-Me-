# The Aaushi Archive

The Aaushi Archive is a two-page guide to my creative work, from experimenting with Photoshop at thirteen to writing and producing songs in Logic Pro.

I created the site for DG8002 Activity 6. For Activity 7, I kept the charcoal and gold design, added a gold border beside my origin story, and changed the skills section so each skill gets its own row on a phone.


## Open the website

Open **index.html** in a browser. No installation, build, account, JavaScript, or internet connection is needed for the two pages and their images. External music, video, project, and profile links require an internet connection.

For an HTTP preview, run this from the repository folder:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>. Stop the server with Ctrl+C.

## Files

```text
index.html                 Homepage: introduction, origin story, abilities
Classified.html            Second page: facts, survival guide, weaknesses, ambitions
style.css                  Shared responsive design and print styles
assets/aaushi-white-fur-portrait.jpg Main portrait of Aaushi
assets/portfolio-photoshop.jpg      Additional Photoshop artwork
assets/portfolio-change-session.jpg Logic Pro session for “Change”
assets/favicon.svg         Original archive monogram
```

The homepage uses lowercase **index.html**, the default entry filename for GitHub Pages. The second page uses **Classified.html**. All links use these exact, case-sensitive names and relative paths so the site works inside a GitHub project repository.

