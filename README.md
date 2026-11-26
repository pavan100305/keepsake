# Keepsake

A photo memories site. Photos you add are saved in this GitHub repository, and the site reads them back from here to display them.

## Set up (about 5 minutes)

1. **Create a repository** on GitHub, for example `keepsake`. It must be public for free GitHub Pages.
2. **Upload these files** to the repository root: `index.html`, `photos.json`, `.nojekyll`, `README.md`.
   On the repository page choose Add file, then Upload files, drag them in and commit.
3. **Turn on GitHub Pages**: Settings, then Pages. Under Build and deployment pick "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
   After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.
4. **Create a token** so the site can save photos for you:
   - Open https://github.com/settings/personal-access-tokens/new
   - Repository access: Only select repositories, then pick your Keepsake repository.
   - Permissions: Repository permissions, Contents set to Read and write.
   - Generate the token and copy it.
5. **Open your site**, press **Owner sign-in**, enter your username, repository name and the token, then Connect.
   The token is kept in this browser only. Do not share it or put it in any file.

## Using it

- **Add photos** (or drag pictures onto the page). Each photo is resized and saved to `photos/`, with a small thumbnail in `photos/thumbs/`. Captions, dates, albums and favorites are saved in `photos.json`.
- Anyone with the site link can view the photos. Only a browser signed in with your token can add, edit or delete.
- After you add photos, GitHub Pages rebuilds, which takes about a minute. Until then other devices show the old list. You see new photos right away on the device you used.

## Notes

- Everything in a public repository is public, including the photos. Don't add anything you want private.
- GitHub recommends keeping a repository under about 1 GB. Photos are resized to a maximum of 2560 px, usually 300 KB to 1 MB each, which is thousands of photos.
- To sign out on a device, press Owner, then Disconnect. To revoke access everywhere, delete the token on GitHub.
