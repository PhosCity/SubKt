[subkt](../index.md) / [myaa.subkt.tasks.mkvmerge](index.md) / [getMkvInfo](./get-mkv-info.md)

# getMkvInfo

`fun getMkvInfo(file: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`, mkvmerge: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "mkvmerge"): `[`MkvInfo`](-mkv-info/index.md)

Reads metadata such as track and codec information from a Matroska-compatible
file using `mkvmerge`.

### Parameters

`file` - The file to read metadata from.

`mkvmerge` - The path to the `mkvmerge` binary, if not present in your PATH.

### Exceptions

`RuntimeException` - If `mkvmerge` failed.

**Return**
An [MkvInfo](-mkv-info/index.md) instance containing the information read from the file.
