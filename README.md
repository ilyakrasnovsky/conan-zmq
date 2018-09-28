# conan-zmq upgraded fork

**Motivation**: Wanted libzmq version [4.2.4](https://github.com/zeromq/libzmq/releases/tag/v4.2.4), but [conan-zmq](https://github.com/bincrafters/conan-zmq) wasn't that far yet (latest 4.2.2). And specifically on Windows, this caused us to suffer the performance consequences of this [bug](https://github.com/zeromq/libzmq/issues/2479), which was fixed in 4.2.3. Plus, before Conan, we were using 4.2.4, so for the sake of consistency, we want to ship Conan packages for 4.2.4. Note that this affects [conan-cppzmq](http://gitty.corp.idtus.com/IKrasnovsky.low/conan-cppzmq).


[Procedure](http://gitty.corp.idtus.com/snippets/77)