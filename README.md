# dotfiles
My dotfiles managed by [chezmoi](https://www.chezmoi.io/)!

---

## Quick start

### Step by step

1. Initialize chezmoi with this dotfiles repo:
`chezmoi init https://github.com/SimmonsHsia/dotfiles.git`

2. Check what changes that chezmoi will make:
`chezmoi diff`

3. If you are happy with the changes then run:
`chezmoi apply -v`

    If you are not happy with the changes then editor it with:
    `chezmoi edit $FILE`

    Or, invoke a merge tool to merge changes with:
    `chezmoi merge $FILE`

### Single command

Install these dotfiles with a single command:
`chezmoi init --apply SimmonsHsia`

### Update

You can pull and apply the latest changes from this remote repo with:
`chezmoi update -v`
