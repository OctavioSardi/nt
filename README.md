# nt: New Task 

`nt` is an opinionated bash script designed to make it easier (and prettier) to create new tasks for **Taskwarrior**. It is heavily inspired by `TASKADD` by Bryan Jenks.

## Dependencies
- `gum`
- `fzf`

## Install

- Clone this repo and either move or symlink `nt` into `.local/bin`
- _AUR is coming soon..._

## Usage

Make sure that `nt` is executable. In Linux you can run `chmod +x nt` inside the repo to achieve that.

After that, simply run `nt` in your shell and it will prompt a form that will eventually create a task.

If you want to omit a certain field (like my own UDAs `estimate` and `brainpower`) you can simply press enter without any value so that field is empty.

Feel free to fork and modify the script as you wish. I'll try to keep working a bit on it but I believe it is mostly finished as is.
