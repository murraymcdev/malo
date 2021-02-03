# Pacman
An old classic written in HTML5.

## Clone Pacman
Clone from GitHub and go into the directory.

```
$ git clone -b gh-pages https://github.com/caleorourke/pacman.git
$ cd pacman
```

## Duplicate Pacman
Make a fresh clone and go into the directory (example).

```
$ git clone https://github.com/username/mrpacman.git
$ cd mrpacman
```

Create a new `gh-pages` branch.

```
$ git checkout --orphan gh-pages
```

Copy the contents from `/pacman` to `/mrpacman`.

```
$ cp -r ~/pacman/* ~/mrpacman
```

Push your code to GitHub.

```
$ git add .
$ git commit -a -m "first commit"
$ git push origin gh-pages
```
