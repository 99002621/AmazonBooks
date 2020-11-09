# Amazon Top 50 Bestselling Books 2009 - 2019

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/17ed7b21ec3c4597b2aa6f075a4949e7)](https://app.codacy.com/gh/99002621/AmazonBooks?utm_source=github.com&utm_medium=referral&utm_content=99002621/AmazonBooks&utm_campaign=Badge_Grade)
![Unit test](https://github.com/99002621/AmazonBooks/workflows/Unit%20test/badge.svg)
![cppcheck-action](https://github.com/99002621/AmazonBooks/workflows/cppcheck-action/badge.svg?branch=master)
![Valgrind](https://github.com/99002621/AmazonBooks/workflows/Valgrind/badge.svg?branch=master)
![C/C++ CI](https://github.com/99002621/AmazonBooks/workflows/C/C++%20CI/badge.svg?branch=master)

##  Design
1. Book Base class
    1. Data Members: 
        * Name
        * Author
        * Year
        * Genre
    2. Derived class seller(AmazonBook)
        * Price
        * user rating
        * reviewCnt
