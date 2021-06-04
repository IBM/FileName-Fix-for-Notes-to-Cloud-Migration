<p align="center">
  <h3 align="center">FileName Fix for Lotus Notes to Cloud Migration</h3>

  <p align="center">
    This open source utility can fix file name issues while migrating data from Lotus Notes to MongoDB and IBM COS
    <br />
    <a href="https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation">Scope</a>
    ·
    <a href="https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation/issues">Report Bug</a>
    ·
    <a href="https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation/issues">Request Feature</a>
  </p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->

## About The Project

Lotus Notes has been used to develop Workflow and Repository applications for many years. It is used as a repository for huge amount of data of various types (pdf, xls, doc, mov, wmv, jpg etc). It is used Globally by IBM Customers/Users.

There are many instances where a user uploads attachments to lotus notes database with file names that contains special characters. Lotus Notes does not stops user in doing so by default. But the problem comes when you try to migrate that file from Lotus Notes to MongoDB or IBM Cloud Object Storage.

I have created solutions to migrate data from Lotus Notes to MongoDB and IBM Cloud Object Storage

Lotus Notes to MongoDB Migration - https://github.com/IBM/Lotus-Notes-to-MongoDB-Migration Lotus Notes to IBM Cloud Object Storage migration - https://github.com/IBM/Lotus-Notes-to-IBM-Cloud-Object-Storage-Migration

You can refer to this repositories for complete migration code.
But this fails to migrate attachments if they contain any special character in file name.

This project presents a method that can fix this issue.

### Built With

- [Python](https://www.python.org/downloads/)
- [Domino Access Service API](https://ds_infolib.hcltechsw.com/ldd/ddwiki.nsf/xpAPIViewer.xsp?lookupName=IBM+Domino+Access+Services+9.0.1#action=openDocument&content=catcontent&ct=api)
- [MongoDB](https://www.mongodb.com/try/download/community)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

You need to install following Python packages

- pip

```sh
pip install pymongo
pip install csv
pip install requests
pip install traceback
pip install re
pip install quopri
```

You need to configure Domino Access Service API on your Domino server and database. Here are the instruction to setup and enable that, <br />
[Instructions to setup and enable Domino Access Service API][documentation-file]

### Installation

1. Clone the repo

```sh
git clone https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation.git
```

2. Install Python packages

```sh
pip install
```

<!-- USAGE EXAMPLES -->

## Usage

please refer to the [Documentation][documentation-file]

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

This code pattern is licensed under the Apache Software License, Version 2. Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache Software License (ASL) FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)

<!-- CONTACT -->

## Contact

Kirti Jha - kirtijha@in.ibm.com

Project Link: [https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation](https://github.com/IBM/FileName-Fix-for-Notes-to-Cloud-Migation)

<!-- MARKDOWN LINKS & IMAGES -->

[documentation-file]: documentation/File%20Name%20Fix%20for%20Notes%20to%20Cloud%20Migration.docx
