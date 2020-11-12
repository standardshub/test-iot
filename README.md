# test-iot
https://api.github.com/users/<username>
  

## Licenses
This section provides a recommendation on how to communicate software or document licenses information in a project.

### Software Licenses

Ideally, the project SHOULD communicate the software license information via three different metods:

* In the README file
* Inside of the repository with a ```License.md``` document
* Inside of each code file created by the group

#### Statement in README File
Insert in the README file one of these statements, (depending of the license type):

```
![APM license](https://img.shields.io/badge/License-MIT-brightgreen)

![APM license](https://img.shields.io/badge/License-Apache_2.0-brightgreen)

![APM license](https://img.shields.io/badge/License-Mozilla_Public_License_2.0-brightgreen)
```

The README file will display one of these three licenses:

![APM license](https://img.shields.io/badge/License-MIT-brightgreen)

![APM license](https://img.shields.io/badge/License-Apache_2.0-brightgreen)

![APM license](https://img.shields.io/badge/License-Mozilla_Public_License_2.0-brightgreen)


#### License File in the Repository
Insert in the repository a file called ```License.md```. 

The Maintainer or Chair can copy the corresponding license file from the [templates/license](https://github.com/OpenManufacturingPlatform/templates/tree/development/License) repository and upload it to the project repository.


#### License Reference in each Source Code File
The recommendation is that projects use [SPDX short-form license identifiers](https://spdx.dev/ids/) in all source code and documentation files that are **original to the project**.


Each source code created by the project SHOULD have one of these SPDX license identifier: (depending of the type of source code license allocated to the project):

**for a MIT license:**

```
# SPDX-License-Identifier: MIT
# Copyright Contributors to the Open Manufacturing Platform
```

**for a Apache 2.0 license:**

```
# SPDX-License-Identifier: Apache-2.0
# Copyright Contributors to the Open Manufacturing Platform
```

**for a Mozilla Public License 2.0 license:**

```
# SPDX-License-Identifier: Mozilla-Public-License-2.0
# Copyright Contributors to the Open Manufacturing Platform
```

If the project needs to include source code / documents from a different upstream project, the recommendation is to retain those files in **unmodified form**  _**(don't add identifiers)**_.
Also consider to:
* keep these files in sync with upstream project
* ask to the upstream project to insert the identifiers on their source code files / documents.

### Document Legal Statement
In projects where the main deliverable are technical documents, each document MUST have a legal disclaimer.

The legal disclaimer to insert in each document SHOULD be:

```
© OMP 2020, All rights reserved.

“THESE MATERIALS ARE PROVIDED “AS IS.”  The parties expressly disclaim any warranties (express, implied, or otherwise), including implied warranties of merchantability, non-infringement, fitness for a particular purpose, or title, related to the materials. The entire risk as to implementing or otherwise using the materials is assumed by the implementer and user. IN NO EVENT WILL THE PARTIES BE LIABLE TO ANY OTHER PARTY FOR LOST PROFITS OR ANY FORM OF INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER FROM ANY CAUSES OF ACTION OF ANY KIND WITH RESPECT TO THIS DELIVERABLE OR ITS GOVERNING AGREEMENT, WHETHER BASED ON BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE), OR OTHERWISE, AND WHETHER OR NOT THE OTHER MEMBER HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.”
```
