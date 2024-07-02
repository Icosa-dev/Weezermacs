# Weezermacs: Keeping Emacs Weezy

Weezermacs is an elisp program that displays an ASCII art version of Weezer's self-titled debut album.

## Installation
To install weezermacs start by changing directory to the directory where your `init.el` file is. Then run the following

```
git clone https://github.com/H4drian/weezermacs.git
```

Then in your `init.el` file add this line of code:

```
(load-file (expand-file-name "weezermacs/weezermacs.el" (file-name-directory load-file-name)))
```

Then you can reload emacs and the command will be fully functional.

## Usage

```
M-x weezer
```
