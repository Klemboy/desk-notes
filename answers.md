# Exercise 1

## 3. Git status

Output:

## main...origin/main

This means that the local `main` branch is tracking the remote
`origin/main` branch. The two branches are currently synchronized,
with no commits ahead or behind.

## 4. SSH keys

The `id_ed25519` file would be a security incident because it is the
private SSH key and must never be committed or shared.

The `id_ed25519.pub` file is harmless because it is the public key,
which is designed to be shared with services such as GitHub.