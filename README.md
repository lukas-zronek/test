# macOS_toolbox

## Synopsis

macOS_toolbox is a replacement for busybox/toybox for macOS. It combines several macOS command line utilities in a single executable. It works very much like crunchgen: It compiles unmodified source code and links it together into a single file.

## Building

**Install Xcode Command Line Tools
```
$ xcode-select --install
```

**Download files
```
$ git clone https://github.com/lukas-zronek/macOS_toolbox.git
```

**Compile
```
$ cd macOS_toolbox
```
```
$ ./build
```

## Usage

```
./toolbox COMMAND
```

If no command is given, all included programs will be listed:

```
./toolbox
Included programs:
	uuencode
	uudecode
	mesg
	write
	chflags
	chmod
	chown
	cksum
	compress
	cp
	dd
[...]
```

## License

macOS_toolbox is released under 2-clause BSD License.
With the exception of source code in the extern directory, which falls under the license specified in the respective files.
