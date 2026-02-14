# Deployment Instructions

**CRITICAL: File Structure**
Your repository must have all files in the **ROOT** directory. Do not use a `data/` folder.

1.  **Verify Your Files**:
    Your repository should look fastly like this:
    ```
    /
    ├── .nojekyll       (Required)
    ├── index.html
    ├── app.js
    ├── styles.css
    ├── profile.json
    ├── services.json
    └── portfolio.json
    ```

2.  **Commit Everything**:
    -   Commit all these files to the main branch.
    -   Ensure `.nojekyll` is included.

3.  **GitHub Pages Settings**:
    -   Source: `main` branch.
    -   Folder: `/` (root).

4.  **Verify Deployment**:
    -   Visit your URL.
    -   If you see "System Initialization Failed", check if `profile.json` is accessible at `your-url/profile.json`.

5.  **Admin Setup**:
    -   Click "Admin" (bottom right).
    -   Enter GitHub Token and Repo Name.
