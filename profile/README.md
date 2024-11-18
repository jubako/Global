## Jubako project

Jubako organization is the mother organization of Jubako project and friend as Arx or Waj

### Jubako

Jubako is a new, fast, flexible container format. It allows to store huge data set, either compressed or not, in efficient manner.
It provide random access on the data. Data (and metadata associated) format is flexible: It is not defined in the Jubako format but in its usecases.
This allow to build arx (a file archive) and waj (a static web site storage).

Jubako repository hosts:
- The specification of Jubako format
- A base library (in Rust) to create and parse Jubako containers
- A set of tools to manipulate jubako containers and explore their content.

### Arx

Arx is a new file archive format. It is equivalent to tar, zip and such. However it provides great advantage compare to them:
- Multi platform
- Efficient compression
- Random access: arx archive can be directly mounted on a directory without prior decompression

See [arx repository](https://github.com/jubako/arx) for futher information.

### Waj

Waj is a static web site storage. It is equivalent to zim file format. As zim file, it allows to :
- Store static web content
- Serve it directly without prior decompression

Waj is still in development, few features are missing compare to zim, mostly fulltext indexation.
However, thanks to Jubako format, it provides already few interesting features:
- Better multithreading while decompressing
- Be able to split content in different packs. (As textual content versus images). The same waj file can be a "noimg" archive and be upgraded to a full archive by adding the missing pack.

See [waj repository](https://github.com/jubako/waj) for futher information.


## Contributions

Contributions are welcomed. No need to know rust, you can already:
- Use arx or waj tools.
- Report any issue/bug in their bug trackers.
- Write documentations, blog posts ...
- Open [discussions](https://github.com/orgs/jubako/discussions) to speak about your use cases or ask any questions.
- Of course, write PR if you can fix isssues.

## Sponsoring

I ([@mgautierfr](https://github.com/mgautierfr)) am a freelance developper. All jubako projects are created on my free time which compete with my paid time.
If you want me to be able to spend more time on Jubako projects, please consider [sponsoring me](https://github.com/sponsors/jubako)
