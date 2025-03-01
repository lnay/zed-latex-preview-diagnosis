# Diagnosis for forwards/inverse search with zed-latex

These are the instructions for providing information related to any issues with the out-of-the-box build+forwards/inverse search which should work out of the box in Zed.

## Instructions:
- download/clone this repository
- remove any settings for texlab in your global Zed settings
- open this folder (fresh with no extra content) as a workspace in Zed
- open `main.tex` from inside Zed and save it (optionally make a small edit before saving)
- wait a couple seconds
- [optional] try inverse-searching as described in the zed-latex or texlab wiki for your PDF viewer
- close the Zed window (delaying this will lead to a very large log file)

## Report the following in your GitHub issue:
- does a `main.pdf` appear next to `main.tex` as expected?
- does a `main.synctex.gz` also appear?
- did the PDF viewer open on its own after saving `main.tex`?
- how does the behaviour differ from what is expected?
- provide the contents of the log file `texlab.log`

## General info:
- operating system:
  - MacOS
  - Linux distro (and which desktop environment)
  - ~~Windows~~ (this feature doesn't explicitly support Windows)
- PDF viewer and its version
- [optional: inverse search issue on Linux only] what is the command to open Zed from the terminal?

