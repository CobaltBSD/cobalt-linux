# Cobalt Linux
A micro-distribution of Linux based off of Cobalt BSD. This is not really a full distribution, but a solid starting point for you to build and maintain your own unique system, if you are into that sort of thing. In particular, you will find use for it if you want to have control of *literally* every aspect of your system, to a degree that not even Gentoo provides.

Cobalt Linux is also designed with conformity as a goal, as the BSD variant makes little effort to align with other systems. For this reason, it uses glibc and gcc.

Cobalt Linux contains no package manager, other than the `pkg` shell script which provides a way of automating the build process. Other than what is provided on install, how you maintain your system is up to you. Of course, distribution-agnostic package managers like Nix and pkgsrc are good options as well, but out of scope for the base system provided.

Furthermore, Cobalt Linux can be installed in a sandbox within another distribution
