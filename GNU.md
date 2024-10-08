 # History of GNU/Linux 

WARNING: This literature review has been curated with the help of an LLM through the [Cursor AI](https://www.cursor.com/) interface and has not been independently verified yet.

(work in progress)

The GNU Project was launched by Richard Stallman on September 27, 1983, to create a free Unix-likeoperating system. GNU is a recursive acronym for "GNU's Not Unix!".
## Widely Used GNU Utilities and Programs

- [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) ([Brian Fox](https://en.wikipedia.org/wiki/Brian_Fox_(computer_programmer)), 1989) The Bourne Again Shell, a widely used command processor.
- [Core Utilities](https://en.wikipedia.org/wiki/GNU_Core_Utilities) (David MacKenzie, 1992) Basic file, shell, and text manipulation utilities.
- [Compiler Collection (GCC)](https://en.wikipedia.org/wiki/GNU_Compiler_Collection) ([Richard Stallman](https://en.wikipedia.org/wiki/Richard_Stallman), 1987) A compiler system supporting various programming languages.
- [Emacs](https://en.wikipedia.org/wiki/GNU_Emacs) ([Richard Stallman](https://en.wikipedia.org/wiki/Richard_Stallman), 1985) An extensible, customizable text editor.
- [Make](https://en.wikipedia.org/wiki/Make_(software)#GNU_Make) ([Richard Stallman](https://en.wikipedia.org/wiki/Richard_Stallman), 1988) A build automation tool.
- [Debugger (GDB)](https://en.wikipedia.org/wiki/GNU_Debugger) ([Richard Stallman](https://en.wikipedia.org/wiki/Richard_Stallman), 1986) A portable debugger.
- [Binutils](https://en.wikipedia.org/wiki/GNU_Binutils) (Steve Chamberlain, 1990) A collection of binary tools.
- [Wget](https://en.wikipedia.org/wiki/Wget) ([Hrvoje Nikšić](https://en.wikipedia.org/wiki/Hrvoje_Nik%C5%A1i%C4%87), 1996) A network downloader.
- [Tar](https://en.wikipedia.org/wiki/Tar_(computing)) ([John Gilmore](https://en.wikipedia.org/wiki/John_Gilmore_(activist)), 1988) An archiving utility.
- [Sed](https://en.wikipedia.org/wiki/Sed) ([Lee E. McMahon](https://en.wikipedia.org/wiki/Lee_E._McMahon), 1974) A stream editor for filtering and transforming text. Adopted by GNU in the 1980s.

## History of GNU Core Utilities

The GNU Core Utilities, or coreutils, is a package of GNU software containing reimplementations of many basic Unix tools. It was created to provide a consistent and free set of tools for Unix-like operating systems. The coreutils package combines three formerly separate packages: fileutils, shellutil and textutils. Here are some of the most important utilities (see the footnotes for details):

- [ls](https://en.wikipedia.org/wiki/Ls), [cp](https://en.wikipedia.org/wiki/Cp_(Unix)), [mv](https://en.wikipedia.org/wiki/Mv), [rm](https://en.wikipedia.org/wiki/Rm_(Unix)), [chmod](https://en.wikipedia.org/wiki/Chmod), [chown](https://en.wikipedia.org/wiki/Chown), [cat](https://en.wikipedia.org/wiki/Cat_(Unix)), [echo](https://en.wikipedia.org/wiki/Echo_(command)) [^1]
- [touch](https://en.wikipedia.org/wiki/Touch_(command)) [^2]
- [date](https://en.wikipedia.org/wiki/Date_(Unix)), [head](https://en.wikipedia.org/wiki/Head_(Unix)), [tail](https://en.wikipedia.org/wiki/Tail_(Unix)) [^3]
- [grep](https://en.wikipedia.org/wiki/Grep) [^4]
- [awk](https://en.wikipedia.org/wiki/AWK) [^5]
- [find](https://en.wikipedia.org/wiki/Find_(Unix)) [^6]

[^1]: Original Unix Author: Ken Thompson; Original Unix Release: circa 1971-1973; GNU Implementation: Richard Stallman; GNU Initial Release: 1980s (exact dates vary); Included in GNU Coreutils: 1992

[^2]: Original Unix Author: Unknown (part of early Unix); Original Unix Release: 1970s; GNU Implementation: Richard Stallman; GNU Initial Release: 1980s; Included in GNU Coreutils: 1992

[^3]: Original Unix Author: Unknown (part of early Unix); Original Unix Release: 1970s; GNU Implementation: David MacKenzie; GNU Initial Release: 1980s; Included in GNU Coreutils: 1992

[^4]: Original Unix Author: Ken Thompson; Original Unix Release: 1974; GNU Implementation: Mike Haertel; GNU Initial Release: 1988; Included in GNU Coreutils: 1992

[^5]: Original Unix Authors: Alfred Aho, Peter Weinberger, and Brian Kernighan; Original Unix Release: 1977; GNU Implementation: Paul Rubin, Jay Fenlason, Richard Stallman; GNU Initial Release: 1988 (as gawk); Note: Not part of GNU Coreutils, but a separate GNU package

[^6]: Original Unix Author: Unknown (part of early Unix); Original Unix Release: 1970s; GNU Implementation: Eric B. Decker, James Youngman, and others; GNU Initial Release: 1990; Note: Part of GNU Findutils, not Coreutils

## State of the Art Before GNU

Before Richard Stallman launched the GNU Project in 1983, the computing landscape was quite different.
- Unix was widely used in academic and commercial settings, but it was proprietary software owned by AT&T.Various Unix versions existed, such as BSD (Berkeley Software Distribution), but they still contained AT&T code. Commercial Unix systems were expensive and came with restrictive licenses.
- Most software was proprietary, and users didn't have the freedom to study, modify, or share the source code.
- PCs were becoming popular, but most ran proprietary operating systems like MS-DOS[^msdos].
- The closed nature of software hindered collaboration and innovation among programmers.

[^msdos]: MS-DOS was first released in 1981, just two years before the GNU Project began. The IBM PC, which popularized the personal computer market, was introduced in 1981 as well. Prior to MS-DOS, early personal computers used a variety of operating systems, including CP/M and Apple DOS. The rapid adoption of the IBM PC and MS-DOS in the early 1980s was part of the changing landscape that motivated Stallman to start the GNU Project.

Stallman's primary goal was to create a completely free Unix-like operating system. He aimed to:

1. Provide users with the freedom to run, copy, distribute, study, change, and improve software.
2. Foster a community of collaborative development and sharing.
3. Ensure that users could control their computing, rather than being controlled by proprietary software vendors.
4. Create high-quality, free alternatives to common Unix utilities and tools.

By launching GNU, Stallman sought to build a complete operating system that respected users' freedoms, which he saw as increasingly threatened by the proprietary software model.

## The Advent of Linux

While GNU was developing its free software components, a crucial piece was still missing: the kernel. This changed with the introduction of Linux:

In 1991, [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds), a Finnish computer science student, [announced](https://groups.google.com/g/comp.os.minix/c/dlNtH7RRrGA/m/SwRavCzVE7gJ) and then [released](https://mirrors.edge.kernel.org/pub/linux/kernel/Historic/old-versions/RELNOTES-0.01) the first version of the Linux kernel.

The Linux kernel quickly gained popularity among developers and enthusiasts, leading to rapid improvements and expansions. The Linux kernel was combined with GNU software to create complete, free operating systems, often referred to as "GNU/Linux" distributions.

**First Distributions**: Early GNU/Linux distributions included:
   - [Softlanding Linux System (SLS)](https://en.wikipedia.org/wiki/Softlanding_Linux_System) (1992)
   - [Slackware](https://en.wikipedia.org/wiki/Slackware) (1993)
   - [Debian](https://en.wikipedia.org/wiki/Debian) (1993)

## Further Reading

- [The early days of Linux](https://lwn.net/Articles/928581/) by [Lars Wirzenius](https://hackerhistory.com/podcast/the-history-of-lars-wirzenius/).