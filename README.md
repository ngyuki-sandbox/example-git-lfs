# hello git lfs

```
$ git ls-tree HEAD
100644 blob 24c35e4cc6f414893b61b831f88623d0e99e77dc    .gitattributes
100644 blob 04fa29257854f1d5be72bb845ebf2626a2e263a3    README.md
100644 blob 8e17032ce6e38f100a8e4d2032142aee7ffcd8fb    blue.png

$ git cat-file blob 24c35e4cc6f414893b61b831f88623d0e99e77dc
*.png filter=lfs diff=lfs merge=lfs -crlf

$ git cat-file blob 8e17032ce6e38f100a8e4d2032142aee7ffcd8fb
version https://git-lfs.github.com/spec/v1
oid sha256:5351645c5e10652b522658a8744d4e79821b994af8b4eb12c658d78ebb9ca321
size 279026
```
