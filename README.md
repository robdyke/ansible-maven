# ansible-maven

Install Maven in latest version from upstream.

# Role variables

- maven_version_major
  - Default: 3

- maven_version_minor
  - Default: 2

- maven_version_patch
  - Default: 5

- maven_mirror
  - Configure the mirror to download Maven.
  - Default: http://mirror.ox.ac.uk/sites/rsync.apache.org/maven

- maven_redis_shad256sum
  - SHA256 sum for the downloaded Maven redistributable package.
  - Default: cdee2fd50b2b4e34e2d67d01ab2018b051542ee759c07354dd7aed6f4f71675c

- maven_bin_path
  - Directory where to symlink the mvn binary to.
  - Default: /usr/local/bin

# Dependencies

None.

# License

Apache Version 2.0


# Author

Revised by Rob Dyke @robdykedotcom opengpsoc.org
Forked / Cloned from original work by Mark Kusch @mark.kusch silpion.de


<!-- vim: set ts=4 sw=4 et nofen: -->
