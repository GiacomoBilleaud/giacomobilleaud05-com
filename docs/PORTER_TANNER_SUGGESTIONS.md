# Portfolio suggestions from Porter Tanner

The three main pages are live and contain real content. These are small finishing steps based on the supplied website assignment and grading rubric. Start with the README and resume printing, then work down the list.

## How to use this

1. Open your website folder in Antigravity.
2. Copy the entire prompt below into Gemini.
3. Review each change in the browser before saving it to GitHub. Ask Gemini to explain anything you do not understand.

A **commit** is a saved checkpoint. **Push** uploads your commits to GitHub. A **pull request (PR)** proposes changes; **merge** applies them to the main branch. This PR adds this checklist. The website fixes still need to be made.

## Copy this into Gemini

```text
Help me finish this existing portfolio for the website assignment. I am new to GitHub. Explain each step simply and keep the current design and real content. Work on a new branch, one numbered task at a time. Show me the changes and help me check them before making each descriptive commit.

1. Improve README.md.
   Add a project title, a short description, the live website link, the repository link, and a short list explaining index.html, resume.html, project.html, and styles.css.
   Live site: https://giacomobilleaud.github.io/giacomobilleaud05-com/
   Repository: https://github.com/GiacomoBilleaud/giacomobilleaud05-com
   Ask me for one real problem I had while directing the coding agent, what I changed, and what I learned. Help me turn MY answer into a specific reflection paragraph. Do not invent an experience or claim I used tools I did not use.

2. Fix resume printing in styles.css.
   The @media print rule hides .off-canvas-wrapper, which also contains the resume. Keep the content wrapper visible and hide only navigation, the sidebar, footer, and unnecessary controls. Check that the resume fits the printed page without clipping. Guide me through Print Preview to confirm the actual resume is visible.

3. Tidy the phone menu button.
   The general button rule applies min-width: 130px to the small menu icon. Add a targeted .menu-icon override for its size and spacing. Keep the regular buttons looking the same. Check that the menu opens, closes, and reaches all three pages on a phone-sized screen.

4. Make contacting me straightforward.
   The current contact form uses mailto and depends on the visitor having an email app configured. Replace it with a visible email address and a clearly labeled email link using the existing address. Explain that the link opens an email app. Keep the other contact links. Do not add a backend or send a test message.

5. Clarify the home page content.
   Add a short work-experience section using only actual roles, employers, and dates already in resume.html. Keep fuller details on the resume page.
   The site labels this assignment ISDS 3107, while the supplied assignment is ISDS 3100. Ask me to confirm the correct course before changing assignment labels. Preserve legitimate references to other courses or projects.

6. Clean up the repository carefully.
   Remove the tracked .DS_Store file and add .DS_Store to .gitignore.
   Check whether portfolio.html is an unused older page before removing it. Keep all images and presentations that the current pages use, including the numbered PNG files. Keep useful preview tools such as server.ps1.

7. Verify the finished site and help me publish the fixes.
   Check Home, Resume, and Project navigation in both directions, images, downloads, and contact links. Check desktop and phone widths of 320px and 390px, plus a second browser. If you cannot test something, give me a simple manual check and say it is still unverified.
   Save completed improvements in separate, meaningful commits. The rubric asks for at least 5 commits across 3 calendar days. The reviewed main branch had 3 commits across 3 days, so it needs more real development checkpoints. Do not create empty commits or change dates. Help me push the branch and open a PR, then review it with me before merging. After merging, verify the final main-branch history and the live GitHub Pages site.
```

## Notes for the review

- Reviewed main commit: `615301cef82b8b1e761ab95276d09ea46eb867da`.
- The printing issue was identified in the CSS; an actual Print Preview check is still needed.
- These suggestions target README/reflection, functionality, structure, repository organization, and version-control criteria. They are not a guaranteed grade.

Suggested by Porter Tanner.
