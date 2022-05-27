```bash
Usage: mkdummy [-f files] [-n bytes] [-x bytes] [-s bytes] [-d depth] [-r [0..99)] [path]
  -d: [D]epth of recursive folder nesting
  -f: maximum number of [F]iles
  -n: mi[N]imum file size (in bytes)
  -r: probabilty of [R]ecursive folder nesting [0..100), default 10
  -s: approximate amount of disk[S]pace to consume (in bytes)
  -x: ma[X]imum file size (in bytes)
  ```
  
  Requires installation of no new dependencies in macOS. Generates files of random content with quasi-realistic file names and extensions, within a nested folder hiearchy.