# decompress-maybe
Transform stream that decompress its input if it's compressed, and echoes it if not

This module accept a stream compressed using `gunzip` or `bzip2` formats and
output the decompressed stream. In case the input stream was already
decompressed it returns it as-is. More compression formats could be added in the
future, pull-requests are welcome :-)

This is a collaboration project between @mafintosh and @piranna.
