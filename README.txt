MUN Self-Service Redesign - Interactive prototype
COMP 3150 Assignment 3 - Prabh Preet Singh

How to open: unzip this folder and double-click index.html.
It opens in any web browser (Chrome, Edge, Firefox, Safari). No internet or installation needed.

Every button works, including all five day buttons, Drop/Undo on every course, course search
and Add, Review changes and Confirm, and the Grades, Exams, Fees, Transcript and Apply to
Graduate pages. The browser's Back button works. Reload the page to reset it.
See Section d of Singh_A3.pdf for the user flow to follow.

Host on GitHub Pages
--------------------
This is a static website. No installation or build command is required.

1. Create a public GitHub repository named assignment_HCI (or use an existing one).
2. Use Add file > Upload files to upload index.html and README.txt to the repository
   root, not inside an extra Singh_prototype folder. Include .nojekyll if uploading
   with Git; when using the browser, use Add file > Create new file to create it
   with an empty line if it was not included in the upload.
3. Commit the files to the main branch.
4. Open the repository's Settings > Pages.
5. Under Build and deployment, set Source to Deploy from a branch.
6. Select main and /(root), then click Save.
7. Wait for deployment to finish. The Pages settings will show the live site URL,
   normally https://YOUR-USERNAME.github.io/assignment_HCI/.

The .nojekyll file tells GitHub Pages to serve the static files directly.
Navigation uses URL hashes, so prototype pages work within a repository subpath.
To publish an update, replace index.html and commit it to the same branch.
