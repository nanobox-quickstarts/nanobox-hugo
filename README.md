# Hugo from scratch

Run a Hugo app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>

## Clone the repo

```bash
# clone the code
git clone https://github.com/fkumro/nanobox-hugo.git

# cd into the hugo app
cd nanobox-hugo
```

## Run the app

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local hugo.dev

# Run Hugo, specifying the address to bind to and the dns entry for the base URL
nanobox run hugo server --bind=0.0.0.0 --baseURL=http://hugo.dev/
```

## Check it out

Visit your app at <a href="http://hugo.dev:1313" target="\_blank">hugo.dev</a>

## Explore
With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# display the version of Hugo installed
hugo version

# and your code is mounted
ls
```

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>