# basic-rpm-create
Example of a basic rpm creation 

In this example, you need work from your $HOME directory.


1.) Setup $HOME/.rpmmacros

 cd $HOME
 git clone https://github.com/chanslor/basic-rpm-create.git
 cd basic-rpm-create
 cp .rpmmacros  $HOME

2.)
 cd $HOME/basic-rpm-create/SPECS
 rpmbuild -bb hello.spec

 Should have created rpm in  $HOME/basic-rpm-create/RPMS/
/play letitgo
