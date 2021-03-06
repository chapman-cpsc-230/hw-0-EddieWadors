# Instructions

## This Assignment

* Clone this repository to your local machine.
* Edit the README.md file according to the instructions below.
* Perform a ```commit``` so our local repository remembers the edits you've made
* Now push the results back to the github repository (the ```sync``` button does this)

## General



* Edit the README.md file:
    * Change _\<your name\>_ and _\<date\>_ at the beginning of the file
    * Edit the line ```[![Build Status](https://img.shields.io/travis/ChapmanCPSC230Spring16/YYYYYYYY.svg)](https://travis-ci.org/ChapmanCPSC230Spring16/YYYYYYYY)``` replacing ```YYYYYYYY``` with the name of this repository (should be something like ```HW1<your git name>```)
    * Reread the __Honor Pledge__ again and 'sign' it with your name at the end
    * Add your own text in the __Description__ and __What I Learned__ sections


* Connnect the repository to Travis CI
    * On the github site, go to ```settings``` then to ```Webhooks & services```
    * Then click on ```Add service``` and scroll to ```Travis CI```.
    * This takes you to a new page. Scroll to the bottom and click ```Add service```


* Correctly document each source file
    * At the top of each source file (```.py``` file), include a docstring in te following format

    ```
    """
    File: <filename>

    Copyright (c) 2016 <your name>

    License: MIT

    <brief description of the code>
    """    
    ```

* Ensure that what you push to the github repository builds correctly (the build badge displays as [![Build Status](https://img.shields.io/travis/ChapmanCPSC230Spring16/Assignment-X.svg)]()) in the README file.
