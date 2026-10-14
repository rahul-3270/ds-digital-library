# DS Digital Library — DS-1 theme update

## What changed
- White + soft green theme.
- Profile photo updated to the supplied photo (`images/profile.jpg`).
- Register number changed to `24102A030028`.
- Section changed from `DS-3` to `DS-1`.
- Existing pages and navigation retained.
- Login page renamed to `index.html` so static hosting opens it automatically.

Note: The original student name is unchanged because a replacement name was not supplied. Update it in `index.html` and `dashboard.html` if needed.

## Preview on your computer
1. Extract this ZIP.
2. Open the `DS1_Data_Science_Digital_Library` folder in VS Code.
3. Install the VS Code extension **Live Server**.
4. Right-click `index.html` → **Open with Live Server**.
5. Test the login/dashboard, modules, profile photo, and coding lab.

The existing JavaScript demo login currently uses the register number `24102A030028` and password `1234`. This is only a front-end demo, not secure authentication.

## Create a public website URL with GitHub Pages
1. Sign in at https://github.com/ and create a new **public** repository, for example `ds1-digital-library`.
2. Extract the ZIP, then upload the *contents* of this folder to the repository root (so `index.html` is at the root, not inside another nested folder).
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to publish. The URL will look like `https://YOUR-USERNAME.github.io/ds1-digital-library/`. Replace `YOUR-USERNAME` with your GitHub username and use the actual URL shown in Settings → Pages.

Important: Do not upload private student information or use a public repository if you do not want the photo/register number visible. A public static site is visible to anyone with the URL. The supplied project did not include the PDF files or the original MBU logo; the logo reference is replaced by a simple DS Digital logo, and module PDF links will work only after you add the matching PDFs under a `pdfs` folder.
