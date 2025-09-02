I just recently started using nix.

IT’S AN ABSOLUTE GAMECHANGER.

Previously, you always had to make sure that you had certain dependencies already installed.

This is not the case with nix anymore.

Nix creates your development environment for you, from the ground up.

Previously, you never had a reliable way to set up a development on *anyone's* machine. Local development environments become bulky, because the only way to realize them is to Dockerize *everything*.

Note: It does NOT protect you from bad programs. It’s not containerization, it’s not virtualizations. Just the way how the packages are installed is guaranteed to be consistent across platforms, i.e. operating systems and computer architectures.

I suggest to always put `systems = [ "aarch64-darwin" "x86_64-darwin" "aarch64-linux" "x86_64-linux" ];` into your `flake.nix`. Simply to at least *aim* by default for full coverage.

On Windows, of course, you'll have to use WSL2.

No one had ever taught me nix, because apart from vibecoding, I didn't significantly advance my development skills in the past, maybe, 5 years. I got too cozy in management.

But making advancements still requires actual coding and *understanding* of computer systems. As above, so below. The macro mirrors the micro. Nix is a perfect example of this. Creating an operating system, simply because *you can*.

In German, `nix` is a colloquialism for `nothing`, by the way. If we would all use `nix`, what would we use?

Ultimate liberation from dependency management.

Thank you, nix.

- Julian, CTO, 2025-09-02
