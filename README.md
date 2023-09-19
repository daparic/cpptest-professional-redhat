### Description

This Docker container image has [Parasoft C/C++test Professional](https://docs.parasoft.com/display/CPPTESTPROEC20231) tool installed 
under `/opt/parasoft/` folder:

- /opt/parasoft/cpptest-professional/cpptest/

### Build Image

```
git clone https://github.com/daparic/cpptest-professional-redhat
cd cpptest-professional-redhat/
docker build -t cpptest-professional-redhat .
```

### Run a container from image

```
docker run -it --rm cpptest-professional-redhat bash
ls -l /opt/parasoft/
```

### Additional Reference

- https://hub.docker.com/r/parasoft/cpptest
