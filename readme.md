# git-github

A little script to ease the process of cloning GitHub repository within a
predefined repository.

## Install

    $ npm install mklabs/git-github -g

It'll install a `git-github` command on your system, which git can use with
`git github`.

## Usage

```shell
# git github <username>/<repo>
$ git github nodejs/docs
... Cloning nodejs/docs in /home/mk/src/ ...
$ git clone git@github.com:nodejs/docs.git /home/mk/src/nodejs/docs
Cloning into '/home/mk/src/nodejs/docs'...
remote: Counting objects: 259, done.
remote: Total 259 (delta 0), reused 0 (delta 0), pack-reused 258
Receiving objects: 100% (259/259), 67.58 KiB | 0 bytes/s, done.
Resolving deltas: 100% (124/124), done.
Checking connectivity... done.
```
