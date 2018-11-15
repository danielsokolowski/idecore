Force.com IDE Core (danielsokolowski fork)
========

This is a fork of the official Force.com IDE with following improvements: 

- Deployment Option: 'Disable 'Save to Server' dirty resource check'
- Deployment Option: 'Disable 'Save to Server' synchronize check'
- Deployment Option: 'Disable 'Save to Server' user confirmation check'


Eclipse IDE Update site: https://raw.githubusercontent.com/danielsokolowski/idecore/master/eclipse-ide-update-site/site.xml


For more information, refer to the [Force.com original repo][1].

TODO
----

- disable automatic switch 'Work Online' when project login/password are updated
- add resource-bundle native support
- add OrchestraCMS development support
  - add copy HTML/JS to pate `getHTML()` conversion
- refactor and simplify code, the massive amount of layers complicated development
- add sfdx support
- update Anonymous Apex to store code snippets within project project directory, ex. `salesforce.executeanonymous`
  - https://github.com/forcedotcom/idecore/issues/2


License
-------

[Eclipse Public License (EPL) v1.0][2]

Getting Started
---------------

Refer to the wiki pages for this repository. You can access those pages
by clicking on the wiki icon in the navigation on the right side of this
page.

Building
--------

To build an external version, issue a `mvn clean package -Dexternal=true`
in this directory. If everything executes successfully, you shall see
the artifacts in com.salesforce.ide.repository.external/target/repository.

Contributing
------------

Please refer to [this][3] wiki page.

[1]: https://github.com/forcedotcom/idecore
[2]: http://wiki.eclipse.org/EPL
[3]: https://github.com/forcedotcom/idecore/wiki/Contributing-Code
