Go Project Setup Using Eclipse
=======
**Make sure to install JDK SE version 8, [Here](http://www.oracle.com/technetwork/java/javase/downloads/index.html)**

**Set go Environment PATH**
```
	export GOPATH=$HOME/goprojects
	export PATH=$PATH:$GOPATH/bin
```

### Windows 
- Add new installation link (Help -> Install New Software..)  `http://goclipse.github.io/releases/`
- Search and Install `GoClipse`
- If you want to see definition and code completion, install two following packages:
	- gocode: `go get -u -ldflags -H=windowsgui github.com/nsf/gocode`
	- godef: `go get -u -ldflags -H=windowsgui https://github.com/rogpeppe/godef`
- Add go bin (Window -> Preferences -> Go -> Tool), point each following `go`, `gocode` and `godef` to execute folder (i.e: `C:\Go\bin`)

### OSX
- Add new installation link (Help -> Install New Software..)  `http://goclipse.github.io/releases/`
- Search and Install `GoClipse`
- If you want to see definition and code completion, install two following packages:
	- gocode: `go get -u github.com/nsf/gocode`
	- godef: `go get -u https://github.com/rogpeppe/godef`
- Add go bin (Window -> Preferences -> Go -> Tool), point each following `go`, `gocode` and `godef` to each execute folder
(i.e: `/usr/local/go`)