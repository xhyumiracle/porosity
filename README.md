installed porosity - the discompiler of Solidity

cd to /tmp before run porosity so that you may use it more comfortablly if you mount 'pwd' to /tmp

place this line in your .bashrc or .zshrc:
`alias porosity='docker run -v `pwd`:/tmp -it --rm xhyumiracle/porosity'`
