# 🦉 Homework Buddy — K–5

**Homework Buddy** is a free, cheerful, mobile-friendly practice app for children in kindergarten through fifth grade. It gives gentle hints, explains answers, and rewards effort with stars.

## Use Homework Buddy
Once GitHub Pages has been enabled, the public test website is:
**https://james7477.github.io/Homework-Buddy/**

For now, you can also download `index.html` and open it in a browser, even without a network connection.

## Homework First test (new)

Try the separate, mobile-friendly **Homework First** test at:
**https://james7477.github.io/Homework-Buddy/homework-test.html**

This page asks children for the **actual assignment** rather than immediately serving preset practice questions. Features include grade K–5 selection, subject and task selection, typed homework, an optional worksheet photo preview (no photo OCR), optional browser speech input, grade-level lesson suggestions, gentle hints, and a simple arithmetic answer checker. Other subjects provide guided questions rather than automated grading. This is an offline-friendly static prototype and **not an AI tutor, school login, or a replacement for the child's teacher**.

No assignment, picture, or voice recording is sent to our server; photos stay in the tab's memory, typed work is not stored by this test page, and only grade selection may be stored locally. Browser speech recognition may use the browser provider's online service. The existing `index.html` practice app is unchanged.

## Features in test v0.1
- Choose **Kindergarten, Grade 1, Grade 2, Grade 3, Grade 4, or Grade 5**
- Choose **Math, Reading, Spelling, Science, or Social Studies**
- **120 guided exercises**: four questions per subject and grade level
- Two progressive **hints**, an answer explanation, retry, and skip
- Optional **Read to Me** using browser-supported speech synthesis
- Earn stars and review simple progress stored on the same browser/device
- Parent Corner with progress reset and privacy explanation
- Responsive layout for phones, tablets, school Chromebooks, and computers

## Children's privacy
This first edition does **not** ask for names, email addresses, schools, photos, or account registration. There are **no ads, third-party analytics, external AI requests, login services, or server databases** in this prototype.

The browser's local storage is used only for a selected grade and completed-activity identifiers. Read-aloud behavior varies by browser and operating system. A future AI tutor, image recognition, or child accounts would require separate security, privacy, and parental-control work.

## Publishing
The repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

**First-time setup by the repository owner:**
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Return to **Actions** and run **Deploy Homework Buddy to GitHub Pages**, or push a new commit.
4. After successful deployment, open **https://james7477.github.io/Homework-Buddy/**.

Subsequent edits to `main` will automatically trigger the deployment workflow. If the repository already has GitHub Pages enabled, no first-time setting change is needed.

## Notes
This is a small starter activity bank, not a full accredited curriculum or a live AI tutor. Adults should review unfamiliar subject matter and help younger children navigate. Keep future children's personal information out of public GitHub files.
