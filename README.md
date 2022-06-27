# 1 Fuzzy Way, 0x50 0x4B.
I'm on my fuzzy way.

## [CVEs](CVEs):

Multiple bugs in Vim Editor (Written in C).

- Heap Overflows: [CVE-2021-3903](CVEs/vim/CVE-2021-3903.md), [CVE-2021-3927](CVEs/vim/CVE-2021-3927.md), [CVE-2021-3973](CVEs/vim/CVE-2021-3973.md), [CVE-2021-3984](CVEs/vim/CVE-2021-3984.md).
- Use of Uninitialized Variable: [CVE-2021-3928](CVEs/vim/CVE-2021-3928.md).
- Use After Free: [CVE-2021-3974](CVEs/vim/CVE-2021-3974.md).

Multiple bugs in tsMuxer which is used by Universal Media Server ([https://www.universalmediaserver.com/about/](https://www.universalmediaserver.com/about/)) internally - Most starred transport stream muxer project on Github (Written in C++).

- Out-of-bounds Read: [CVE-2021-34070](CVEs/tsMuxer/CVE-2021-34070.md) - [Report](https://github.com/justdan96/tsMuxer/issues/426), code is actually from ffmpeg project
- Heap Overflows: [CVE-2021-34067](CVEs/tsMuxer/CVE-2021-34067.md), [CVE-2021-34068](CVEs/tsMuxer/), [CVE-2021-34071](CVEs/tsMuxer/CVE-2021-34071.md), [CVE-2021-35344](CVEs/tsMuxer/CVE-2021-35344.md), [CVE-2021-35346](CVEs/tsMuxer/CVE-2021-35346.md).
- Divide-by-zero: [CVE-2021-34069](CVEs/tsMuxer/CVE-2021-34069.md).

Multiple bugs in ffjpeg project.
- 2 Heap Overflows: [CVE-2021-44956](CVEs/ffjpeg/CVE-2021-44956.md).
- Buffer Overflow in global: [CVE-2021-44957](CVEs/ffjpeg/CVE-2021-44957.md)

## [Harness](Harness):

## [Scripts](Scripts):


