# Your website

- `index.html` is the public site.
- `content.json` holds all your text (bio, publications, experience).
- `admin/index.html` is the editor, at `/admin/` on your live site.

## Publish it (free, about 5 minutes)

1. On GitHub, create a new **public** repository named `YOURUSERNAME.github.io`.
2. Open the repository, choose **Add file → Upload files**, and drag in everything inside this folder (`index.html`, `content.json`, the `admin` folder, this README). Keep the `admin` folder structure. Commit.
3. Go to **Settings → Pages**. Under Build and deployment, choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute, your site is live at `https://YOURUSERNAME.github.io`.

## Use the editor

1. On GitHub, go to **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. Set Repository access to **Only select repositories** and choose your site repository.
3. Under Permissions, set **Contents** to **Read and write**. Generate the token and copy it.
4. Open `https://YOURUSERNAME.github.io/admin/`, enter `YOURUSERNAME/YOURUSERNAME.github.io`, the branch (`main`), and the token. Connect.
5. Edit, then choose **Save changes**. The live site updates in about a minute.

Keep the token private. The editor keeps it only in the open browser tab.
