# Node Package Template

Rebar3 template for packaging `cuttlefish/clique` based OTP releases to
RPM or DEB.

Some assumptions:

- your project is versioned by Git
- package versioning is based on Git tags

## Commands

Tar release:

```
make tar
```

Make archive with all dependencies suitable for compiling and packaging
on target platform without network access:

```
make dist
```

Create platform dependent package:

```
make package
```
