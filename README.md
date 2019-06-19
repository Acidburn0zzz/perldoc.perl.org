# This repository is for bug tracking issues only

In the development of this project it became neccesary to split the engine away from the exported static site, so in total there are three repositories, this one being primarily for bug tracking and feature requests.

Which work in conjunction with the engine and export repositories that are detailed below

## The engine (public repository\*)

perldoc.perl.org-engine is the repository you need for the new docker/pretty version of this repository

This repository is for code storage only

<!-- * currently private scheduled to be made public -->

the repository is now public [here](https://github.com/OpusVL/perldoc.perl.org-engine)

## The output (public internet clonable of the output)

This repository is simply the auto created statically created version of the site and is not interactable except for cloning

perldoc.perl.org-export is the [full site repository](https://github.com/OpusVL/perldoc.perl.org-export)

## Reasons for this repository being cleared and split

During the development of this project at times it was neccesary for large binary files and 200k+ sets of smaller files be created,
beacause of this the '.git' is an enourmous 400MiB and is incredible slow to work with, infact shells that automatically do fancy
things with git (like zsh) will take seconds to even change directories.
