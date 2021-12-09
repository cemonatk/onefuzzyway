# 1 Fuzzy Way ,0x50 0x4B.
On my fuzzy way

CVEs:

Multiple vulnerabilities in Vim Editor (Written in C).

- Heap Overflows: [CVE-2021-3903](CVEs/vim/CVE-2021-3903.md), [CVE-2021-3927](CVEs/vim/CVE-2021-3927.md), [CVE-2021-3973](CVEs/vim/CVE-2021-3973.md), [CVE-2021-3984](CVEs/vim/CVE-2021-3984.md).
- Stack Overflow: [CVE-2021-3928](CVEs/vim/CVE-2021-3928.md).
- Use After Free: [CVE-2021-3974](CVEs/vim/CVE-2021-3974.md).

Multiple vulnerabilities in tsMuxer which is used by Universal Media Server ([https://www.universalmediaserver.com/about/](https://www.universalmediaserver.com/about/)) internally - Most starred transport stream muxer project on Github (Written in C++).

- Out-of-bounds Read: [CVE-2021-34070](CVEs/tsMuxer/CVE-2021-34070.md) - [Report](https://github.com/justdan96/tsMuxer/issues/426), code is actually from ffmpeg project
- Heap Overflows: [CVE-2021-34067](CVEs/tsMuxer/CVE-2021-34067.md), [CVE-2021-34068](CVEs/tsMuxer/), [CVE-2021-34071](CVEs/tsMuxer/CVE-2021-34071.md), [CVE-2021-35344](CVEs/tsMuxer/CVE-2021-35344.md), [CVE-2021-35346](CVEs/tsMuxer/CVE-2021-35346.md).
- Divide-by-zero: [CVE-2021-34069](CVEs/tsMuxer/CVE-2021-34069.md).


