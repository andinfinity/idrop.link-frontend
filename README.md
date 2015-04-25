# idrop.link OSX Client
idrop.link - self hosted personal screenshot and file cloud to share with your friends, colleagues and family

## Development
This project utilizes [CocoaPods](https://guides.cocoapods.org) for dependency management. It needs to be installed befire you can use `pod`.

For the dependencies to be included please be sure to open `idrop.link.xcworkspace` with xcode, and not the regular xcode project file.

The project versioning tries to adhere to the standards of [semantic versioning](http://semver.org). The Git workflow usses a mixture of [this](http://nvie.com/posts/a-successful-git-branching-model/) and the [Git Branching Workflow](http://git-scm.com/book/en/v1/Git-Branching-Branching-Workflows).

Milestones are vaguely defined minor or major version bumps that are being released and merged from the `development` base branch to the `master` branch.

### Documentation
Every API like function, class or other objects have to be documented. For more details on documentation in Swift see [NSHipster](http://nshipster.com/swift-documentation/). We generate the docset with [Jazzy](https://github.com/realm/jazzy) and deploy it in the root directory of the `gh-pages` branch. An online version of the documentation is available on [GitHub](http://andinfinity.github.io/idrop.link-osx).

## License
Copyright (c) 2015 Christian Schulze

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
