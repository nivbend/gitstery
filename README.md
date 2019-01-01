# A Git Murder Mystery
A murder had been committed in Git Town!

To solve it you'll need to muster all your `git` knowledge (or just google a bunch).

### NOTICE
This is a product of another repository, https://github.com/nivbend/gitstery-generator. As such,
contributions are accepted _only_ on that repository and not here. Feel free to post any issues,
suggestions or pull-requests on the "generator" project and improve this game for everyone!

Also, because this is a randomly-generated repository, sharing "public" history is impossible as it
gets rewritten every time. So in contrast to most repositories, this one gets updated by
`git push --force` (though that's usually considered bad practice). If you have a copy of this
repository and want to "pull" the latest version, it would probably be easiest to just delete the
current version and clone this repository again.

## Instructions
Clone this repository (this isn't meant to be solved using GitHub's interface):
```bash
$ git clone https://github.com/nivbend/gitstery.git
$ cd gitstery/
```
Then follow the instructions in `instructions.txt`.

The mystery was built so that solving it can be done with `git` commands and `git` commands alone.
If you want a `git` way of reading the instructions, try:
```bash
git cat-file blob HEAD:instructions.txt
```

## Who is this for?
The target audience are intermediate `git` users, this is not meant to be a tutorial for `git`
newcomers. But feel free to try your hand at this if you'd like! Don't let random `README.md` files
on the internet tell you what you can or cannot do.

# Acknowledgments
This project was inspired by:
* [SQL Murder Mystery](https://mystery.knightlab.com/).
* [The Command Line Murders](https://github.com/veltman/clmystery).
