# basic understanding of how to generate documentation

*note*: a more automatic solution will follow, but this is to give a basic understanding of the process and it will work as a first manual solution

## Prerequisites
   Install, if not already done, python3-sphinx, python3-pip, recommonmark, sphinx_markdown_tables 
   Example on ubuntu:
   ```
   prompt$ sudo apt install python3-sphinx
   prompt$ sudo apt install python3-pip
   prompt$ sudo pip3 install recommonmark
   prompt$ sudo pip3 install sphinx_markdown_tables
   ```

## Steps

1. copy setup.env.template and change to relevant paths
   ``` 
   prompt$ cp setup.env.template setup.env
   ```
2. source setup-file
   ```
   prompt$ source setup.env
   ```
3. generate html documentation
   ```
   make html
   ```
4. package directory build in tarfile
   ```
   tar cvf casual-middleware-documentation.tar build
   ```
5. unpack it where ever needed

