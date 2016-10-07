# What is hasher?

hasher is a tool for building packages in a safe and reproducible manner. All packages in [Sisyphus](https://en.altlinux.org/Sisyphus) repository are built using hasher.

hasher is similar to earlier ApplianceWare/ALT Linux [sandman](http://old.linux.kiev.ua/~mike/docs/livecd/sandman_mini-howto.html), Debian [sbuild](http://packages.debian.org/sid/sbuild)/[pbuilder](http://www.netfort.gr.jp/~dancer/software/pbuilder-doc/pbuilder-doc.html) and also later Fedora [mock](http://fedoraproject.org/wiki/Projects/Mock), but unlike the mentioned tools it is designed and implemented with security in mind. hasher prevents interaction between package being built and host system and also between packages being built.

It's included into [builder starterkit](https://en.altlinux.org/Starterkits/builder) ready-to-use.

# How to use this image

Run:

```console
$ docker run -it --name some-hasher azol/altlinux-sisyphus-hasher
```

Build packages:

[hasher documentation](https://en.altlinux.org/Hasher).
