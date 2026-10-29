# Omar Taha — personal site

Five-page personal site for the RESECON 490AI final project (Piece 2: web presence) and for recruiters. Plain HTML and CSS, no JavaScript, no build step.

## Run it
Double-click `index.html`, or open it in any browser. Every link is relative, so the folder works from anywhere, including a GitHub Pages sub-path.

## Pages
| File | Page |
|---|---|
| `index.html` | Home: the claim, the Messy → Usable demo, three proof rows |
| `about.html` | Summary, what I am looking for, education, certifications, skills |
| `projects.html` | Terminal_X (lead) and the 490AI industry study |
| `resume.html` | Experience and projects table; PDF link once `resume.pdf` exists |
| `contact.html` | Email, LinkedIn, GitHub placeholder |
| `styles.css` | Design tokens at the top, then base, layout, components |

## Demo vs. real
- **Real:** everything about Omar (education, experience, projects, certifications, skills, email, LinkedIn) comes from his résumé and his own brief.
- **Demo:** the small "Messy / Usable" table on Home uses invented rows, labeled "Demo rows, not real figures" on the page.
- **Placeholders:** search for `[PLACEHOLDER]` to find every spot still to fill: the photo, the GitHub link, the résumé PDF, the project summary, and the report / slides / charts links.

## Drop-in files
- `photo.jpg` (or `.png`): the Home page photo block is ready for it; swap the `<figure class="photo">` contents for `<img src="./photo.jpg" alt="Omar Taha" width="360" height="450">`.
- `resume.pdf`: replace the placeholder paragraph on `resume.html` with the download link (the comment in that file shows the line).

## Deploy (GitHub Pages)
Push this folder's contents to a public repo with `index.html` at the root, then Settings → Pages → Deploy from branch `main`, folder `/ (root)`. The site appears at `https://<username>.github.io/<repo>/` after a minute or two. Nothing here gets committed or pushed without Omar's explicit go-ahead.

## Privacy
No phone number, home address, student ID, GPA or transcript anywhere in this folder. Keep it that way.
