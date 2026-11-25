[DEPLOY.md](https://github.com/user-attachments/files/35410842/DEPLOY.md)
# Put the invitation online (about 15 minutes, on a laptop)

## A. Put the files on GitHub (private)
1. Go to github.com, sign in, click **+** then **New repository**.
2. Name: `wedding-invite`. Choose **Private**. Click **Create repository**.
3. Click **uploading an existing file**. Drag in all files from this folder (index.html, og-image.jpg, vercel.json, .gitignore). Click **Commit changes**.

## B. Publish on Vercel
1. Go to vercel.com, click **Sign up**, then **Continue with GitHub**.
2. Click **Add New**, then **Project**, and **Import** `wedding-invite`.
3. Framework Preset: **Other**. Leave everything else as it is. Click **Deploy**.
4. Vercel shows your address, like `wedding-invite.vercel.app`. Open it and check it.

## C. Fix the share preview
1. In GitHub, open `index.html`, click the **pencil** icon.
2. Replace every `YOUR-ADDRESS.vercel.app` with your real Vercel address (4 places near the top). Click **Commit changes**. Vercel updates by itself in about a minute.

## D. Test, then share
1. Open the address on your phone, tap Open the invitation, and check the music plays and everything shows.
2. Send the address on WhatsApp.

To change anything later: edit the file in GitHub (pencil, then Commit). The same address updates.
