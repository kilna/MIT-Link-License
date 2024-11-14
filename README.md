# MIT Link License

The MIT License, modified to require end-user copyright attribution with a link:

```
MIT Link License  https://kilna.github.io/MIT-Link-License/

[ OPTIONAL PROJECT NAME, ] Copyright © [ YEAR ] [ OWNER ] [ URL ]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software; additionally, the copyright
notice with hyperlink or URL shall be presented in a clear and obvious manner to
Software's end-users.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## What is different?

As compared to the MIT License, this license is different in that:

* A project name (optional) can be a part of the copyright notice.
* A URL to the project's page is an exepcted part of the copyright notice
* The following language has been added to the second clause: "additionally,
  the copyright notice with hyperlink or URL shall be presented in a clear and
  obvious manner to Software's end-users"

## How is it expected to be implemented?

Given a copyright notice line of:

```
Project Name, Copyright © 2024 Owner Name http://project.url
```

Software that presents HTML output to users would include a hyperlink as
follows on the primary user interface page, in a manner than is not obscured
(typically in a page footer), to comply with the license:

```
<a href="http://project.url">Project Name, Copyright © 2024 Owner Name</a>
```

This copyright notice can optionally be prefixed by a qualifying phrase to
indicate the nature of the usage, like "Based on" or "Powered by".

For command line software, to comply with the license, the manual and the
primary user interface offering usage information will include the copyright
notice, including link. For example:

```
# toolname -h
USAGE: toolname [OPTIONS]

...

Project Name, Copyright © 2024 Owner Name http://project.url
```

## Why a new license?

As best as I could tell, there were no modified MIT licenses that:

* Requires copyright attribution to be presented clearly to end-users
* Enforces the presentation of a URL or hyperlink as a part of the attribution
* Is indifferent to the implementation of the software being commercial in nature
* Retains all of the other liberties and protections of the MIT license 

## Author

Kilna, Anthony <kilna@kilna.com>

## License

The distinct language of the MIT Link License itself, and this document
describing its use and intent, are licensed as Creative Commons No Rights
Reserved (CC0), the Unlicense, the MIT No Attribution License (MIT-0), the
Zero-Clause BSD License (0BSD), Public Domain, or whichever licensing
model is considered most permissive of an entity, in the jurisdiction
presiding over an entity copying or modifying this content.
