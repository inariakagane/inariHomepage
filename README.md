[Inari Akagane Personal Website](https://inariakagane.com/) Repo

I don't have much to say here other than current development is done using `python3 -m http.server` inside the `./app` folder. Things might get more complicated later.

I removed the images from the repo so I don't clog GitHub with my files. The site should mostly still work, just with broken links.

# Deployment

From inside ./app/

`scp -r $(pwd) <user>@<ip>:/path/to/www`