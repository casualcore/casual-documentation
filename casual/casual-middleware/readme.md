# basic understanding of how to generate documentation

*note*: a more automatic solution will follow, but this is to give a basic understanding of the process and it will work as a first manual solution

## Steps

1. copy setup.env.template and change to relevant paths
   ``` 
   prompt$ cp setup.env.template setup.env
   ```
2. source setup-file
   ```
   prompt$ source setup.env
   ```
3. copy documentation configuration to source directory
   ```
   prompt$ cp conf.py $CASUAL_BUILD_HOME/.
   ```
4. generate html documentation
   ```
   make html
   ```
5. package directory build in tarfile
   ```
   tar cvf casual-middleware-documentation.tar build
   ```
6. unpack it where ever needed

