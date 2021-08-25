# Lab 0 - Setup

This just makes sure you can run programs written in a variety of languages using my docker image. 

# Create your machine
First, [install docker](https://docs.docker.com/get-docker/) on your system.

From _your_ host computer:
```
docker create -it --name cse465 jfemiani/cse465
```
#Start your machine
```
docker start -at cse465
```

# Testing Your Code


Fork https://gitlab.csi.miamioh.edu/CSE465/instructor/lab0.git into the group created for you at https://gitlab.csi.miamioh.edu/CSE465/yourid. 

Then, in a terminal, type
```bash
docker start -at cse465
git clone https://gitlab.csi.miamioh.edu/CSE465/yourid/lab0.git
cd lab0
make check
```

You should see "Success!" printed several times. 

