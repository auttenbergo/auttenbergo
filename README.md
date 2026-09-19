```console
gvaro:~$ whoami
Gigi Gvaramia — Software & DevOps Engineer · Tbilisi
gvaro:~$ cat pitch.txt
I build the platform and the things running on it.
gvaro:~$ curl -L gvaro.dev                     # the CV, as plain text
gvaro:~$ curl -L gvaro.dev/cv.md               # …as Markdown
gvaro:~$ curl -L gvaro.dev/cv.json             # …as JSON
gvaro:~$ curl -sL gvaro.dev/gigi.1 | man -l -  # …as a man page
gvaro:~$ ssh ssh.gvaro.dev                     # …over SSH
```

**[gvaro.dev](https://gvaro.dev)** — read it in the browser, your terminal, or over SSH.

Security: report via `gvaro.dev/.well-known/security.txt` (PGP-signed). The key is
at `gvaro.dev/.well-known/pgp-key.txt` — verify it against this fingerprint:

`A7B5 19B5 952B ED2F D7C5 3A29 725C 1DF5 1C31 A7AF`
