#WDI Learning Objectve Links

File prepared with [Markdown syntax](http://daringfireball.net/projects/markdown/syntax#p)

##Command Line
* [A-Z Index of the command line](http://ss64.com/osx/)
* [pwd: Path of current directory](http://ss64.com/osx/pwd.html)
* [ls -a:  Contents in the current directory (including hidden files)](http://ss64.com/osx/ls.html)
* [touch: Create new files](http://ss64.com/osx/touch.html)
  * An important note about touch.  It's actual function is to change the timestamp of a file.  If the file dosen't exist it creates it.  There is a lot of other functionality associated with this command, which can be reviewed in the link above.
* [mkdir: make directories (create folders)](http://ss64.com/osx/mkdir.html)
* [cd: change directories](http://ss64.com/osx/cd.html)
  * quick tip cd ~/ directory name - will move you immediately to that directory/folder
* [cp: Copy files and directories](http://ss64.com/osx/cp.html)
* [mv: Move files and directories](http://ss64.com/osx/mv.html)
* [rm: Delete files and directories](http://ss64.com/osx/rm.html)
  * quick tip option -rf is commonly used with rm, function is explained in the rm link above
* [subl .: Open files and directories using Sublime](http://www.sublimetext.com/)
* [Sublime command line](http://www.sublimetext.com/docs/3/osx_command_line.html)

## Git and Github
* Explain the difference between Git and Github
  * [Git](http://git-scm.com/) A free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. [About Git](http://git-scm.com/about)
  * [Github](https://github.com/) A web-based hosting service for software development projects that use the Git revision control system. GitHub offers both paid plans for private repositories, and free accounts for open source projects. As of May 2011, GitHub was the most popular code repository site for open source project. source: [wikipedia](http://en.wikipedia.org/wiki/GitHub).  [About Github](https://github.com/about)
* [Git Tutorials](https://www.atlassian.com/git)
  * These tutorials are by a company called [Altassian](https://www.atlassian.com/)
  * On a side note they also have a Git repo product called [Bitbucket](https://www.atlassian.com/software/bitbucket/overview)

## [Ruby](https://www.ruby-lang.org/en/)
* Learning resources:
* [Learn Ruby the Hard Way](http://ruby.learncodethehardway.org/book/)

## Ruby Basics & Strings
* [Ruby Docs 2.0](http://ruby-doc.org/)
* [Ruby Docs 2.0: Integer](http://www.ruby-doc.org/core-2.0.0/Integer.html)
  * Integer is the basis for the two concrete classes that hold whole numbers, Bignum and Fixnum.
* [Ruby Docs 2.0: Float](http://ruby-doc.org/core-2.0.0/Float.html)
  * Float objects represent inexact real numbers using the native architecture's double-precision floating point representation.
* [Ruby Docs 2.0: String](http://ruby-doc.org/core-2.0.0/String.html#method-i-index)
  * A String object holds and manipulates an arbitrary sequence of bytes, typically representing characters. String objects may be created using String::new or as literals.
  * Because of aliasing issues, users of strings should be aware of the methods that modify the contents of a String object. Typically, methods with names ending in “!” modify their receiver, while those without a “!” return a new String. However, there are exceptions, such as String#[]=.

## Ruby Collections
* [Ruby Docs 2.0: Array](http://ruby-doc.org/core-2.0.0/Array.html)
  * Arrays are ordered, integer-indexed collections of any object.
  * Array indexing starts at 0, as in C or Java. A negative index is assumed to be relative to the end of the array---that is, an index of -1 indicates the last element of the array, -2 is the next to last element in the array, and so on.
* [Ruby Docs 2.0: Hash](http://ruby-doc.org/core-2.0.0/Hash.html)
  * A Hash is a dictionary-like collection of unique keys and their values. Also called associative arrays, they are similar to Arrays, but where an Array uses integers as its index, a Hash allows you to use any object type.
  * Hashes enumerate their values in the order that the corresponding keys were inserted.
* [Ruby Docs 2.0: Set](http://www.ruby-doc.org/stdlib-2.0.0/libdoc/set/rdoc/Set.html) - Not widely used but can be very helpful in some situations.
  * Set implements a collection of unordered values with no duplicates. This is a hybrid of Array's intuitive inter-operation facilities and Hash's fast lookup.
    * The equality of each couple of elements is determined according to Object#eql? and Object#hash, since Set uses Hash as storage.
    * Set is easy to use with Enumerable objects (implementing each). Most of the initializer methods and binary operators accept generic Enumerable objects besides sets and arrays. An Enumerable object can be converted to Set using the to_set method.


## Misc
* [Reserved Words in Ruby on Rails](http://reservedwords.herokuapp.com/words?utf8=%E2%9C%93&q%5Bword_or_notes_cont%5D=)
* [Carrierwave](https://github.com/carrierwaveuploader/carrierwave) - a gem for file uploads


