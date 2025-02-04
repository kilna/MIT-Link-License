# MIT Link License

The MIT License, modified to require end-user copyright attribution with a link:

```
MIT Link License  https://kilna.github.io/MIT-Link-License/

<PROJECT NAME> <URL>
Copyright © <OPTIONAL YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above project name(s) and URL(s), copyright notice(s), and this permission
notice shall be included in all copies or substantial portions of the Software;
additionally, the topmost copyright and all project names and URLs shall be
presented in a clear and obvious manner to Software's end-users as a hyperlink
or text.

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

* A project name and URL appear with the copyright notice.
* The second clause has been modified to require inclusion of the project name
  and URL in derived versions of the software, and that the project name, URL,
  any copyright must be presented to the end user.

## Suitability for projects

This license is suitable for user visible GUI, CLI and web content generating
software, but it is not suitable for software lacking end-user facing content.
This license is not appropriate for libraries, APIs, and other non-user-facing
software.

## How is it expected to be implemented?

Given a project name and URL line, and copyright notice line of:

```
Project Name http://project.url
Copyright © 2024 Owner Name 
```

Software that presents graphical user-interactive output such as a GUI or web
interface should include a hyperlink similar to the HTML that follows in a
manner than is not obscured (typically in a page footer, splash screen, "about" 
dialog), to comply with the license:

```
<a href="http://project.url">Project Name - Copyright © 2024 Owner Name</a>
```

Or alternately:

```
<a href="http://project.url">Project Name</a> Copyright © 2024 Owner Name
```

For command line and non-graphical software, to comply with the license, the
primary user interface and documentation offering usage information will
include the project name(s) and URL(s), and copyright notice(s). For example:

```
# toolname -h
USAGE: toolname [OPTIONS]

...

Project Name http://project.url
Copyright © 2024 Owner Name
```

### Modification and redistribution of software

In the case of a modified and redistributed version of the Software, the
modified version must include the project name(s) and url(s) and copyright
notice(s) from the Software from which it was derived, added above the
existing project name(s) and URL(s) and copyright(s), with adjoining
language describing the nature of the license inheritance, e.g.:
"based on", "forked from", "derived from", "powered by".

```
New Project Name http://newproject.url
Copyright © 2025 New Owner Name

Based on

Project Name http://project.url
Copyright © 2024 Owner Name 
```

Likewise, all project names and URLs must be presented to end-users, along with
at least the topmost copyright, e.g.:

```
<a href="http://project.url">New Project Name</a> Copyright © 2025 New Owner Name
Based on <a href="http://project.url">Project Name</a>
```

## Why a new license?

As best as I could tell, there were no reusable, modified MIT licenses that:

* Requires copyright attribution to be presented clearly to end-users
* Enforces the presentation of a URL or hyperlink as a part of the attribution
* Provides a clear way for inherited projects to attribute predecessors
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
