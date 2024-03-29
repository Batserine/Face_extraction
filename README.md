## Face_extraction

Python implementation of face extraction using haar-cascade classifier for frontal faces.

**Extract facedet folder its the latest work.**

### Requirements
The requirements.txt file contains following:
```markdown
1. numpy
2. opencv-python
3. opencv-utils

`[sudo] pip install -r requirements.txt`
```

```
Download the project. Unzip this zip folder.
```

### Installation

You can install this package in two ways:
1. PIP installation
2. ZIP extraction

```markdown
# PIP Installation

Install latest version(2.0) from the [source](https://pypi.org/project/facedet/).
              **or**
`[sudo] pip install facedet`

Then type `python3` **outside** folders' location in terminal. And type these to get output.{outside **facedet** root folder}
`>>> import facedet`
`>>> from facedet import faceext`
`>>> faceext.extract()`

By default this package reads the images (`data2.jpg`) that was already given.

```
```markdown
# ZIP Installation

After extracting zip from the repository. Type this command  **in** file location. {inside **facedet** sub-folder}
`[sudo] python3 faceext.py <path/to/image>` or you can select the images from data folder.

This way you can check for different images.

```
### Remarks
1. This application is applied to Low-resoluted images. Throws an exception if high-resolution given.
2. Loops and Conditional statements are avoided and replaced with numpy arrays to reduce Time Complexity.

### License
This project is licensed under the MIT license.
