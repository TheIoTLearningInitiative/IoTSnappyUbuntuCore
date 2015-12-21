# Introduction


    (amd64)ubuntu@localhost:~$ snappy info
    release: ubuntu-core/15.04/stable
    architecture: amd64
    frameworks: webdm.canonical
    apps: 
    (amd64)ubuntu@localhost:~$ 
    (amd64)ubuntu@localhost:~$ snappy list -v
    Name          Date       Version Developer  
    ubuntu-core   2015-11-13 10      ubuntu*    
    webdm         2015-11-13 0.9.4   canonical* 
    generic-amd64 2015-11-13 1.4     canonical* 
    (amd64)ubuntu@localhost:~$ snappy list -uv
    Name          Date       Version 
    ubuntu-core*  2015-12-09 11      
    webdm*        1-01-01    0.11    
    generic-amd64 2015-11-13 1.4   
    (amd64)ubuntu@localhost:~$ snappy search docker
    Name   Version   Summary 
    docker 1.6.2.005 Docker  
    (amd64)ubuntu@localhost:~$ sudo snappy install docker
    Installing docker
    Starting download of docker
    8.36 MB / 8.36 MB [====================================================================================================================================================] 100.00 % 425.10 KB/s 
    Done
    Starting download of icon for package
    21.58 KB / 21.58 KB [====================================================================================================================================================] 100.00 % 7.52 KB/s 
    Done
    Name          Date       Version   Developer 
    ubuntu-core   2015-11-13 10        ubuntu    
    docker        2015-12-21 1.6.2.005 canonical 
    webdm         2015-11-13 0.9.4     canonical 
    generic-amd64 2015-11-13 1.4       canonical 
