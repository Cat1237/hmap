# hmap

## DumpHeaderMap
Dump `.hmap` file contents.
```sh
DumpHeaderMap <path to hmap file>
```
Example:
```sh
DumpHeaderMap /Users/cat1237/Desktop/Test/testHmap.hmap
```

## WriteHeaderMap
Gen `.hmap` file by parsing the specified json file.

```sh
WriteHeaderMap <path to input json file> <path to output hmap file>
```
Example:
```sh
WriteHeaderMap /Users/cat1237/Desktop/Test/testHmap.json /Users/cat1237/Desktop/Test/testHmap.hmap
```
`JSON` file：
```json
[
    [key, prefix, suffix]
]
```
Example:
```json
[
   ["TestAndTestApp/Dog.h", "/Users/cat1237/Desktop/Test/", "Dog.h"]
]
```

## Also see
[cocoapods-hmap](https://github.com/Cat1237/cocoapods-hmap)
A CocoaPods plugin/Command Line Tool which can gen/read header map file.

