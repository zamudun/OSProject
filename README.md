# OSProject
Group Project for OS Section 6
# OSProject Running Containers for Application Development

Group Name: Tom Tom Bak

Section: 6. 

Team Mates:
1. MUHAMMAD AZAMUDDIN BIN SHAHRIL and 2227153
2. IZZUDDIN NURASHEED BIN ABD RASHID and 2226833
3. MUHAMMAD IRFAN ZAFRI BIN MUHAMAD and 2222645



***Questions:***

1. What is the link of the fork OSProject in your repository. 
```bash
  https://github.com/zamudun/OSProject
```

2. How many files and folders are in this repository.  
 ```bash
  1
 ```
3. What is default OS used to run the virtual environment for codespaces. 
 Linux
4. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . 
```bash
  2 core: 8GB ram 32GB disk. 
  4 core: 16GB ram 32GB disk.
```
5. Why must we commit and sync our current work on source control? 
  To ensure the changes are saved and accessible to different team members.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ pwd
/workspaces/OSProject
```

2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
```

3. Run the command **df** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10701820  20451760  35% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 13090684  17191108  44% /vscode
/dev/sda1       46127956 18672084  25080296  43% /tmp
/dev/loop4      32847680 10701820  20451760  35% /workspaces
```

4. Run the command **du** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ du
8       ./.git/refs/heads
4       ./.git/refs/tags
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
32      ./.git/refs
68      ./.git/hooks
8       ./.git/info
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/branches
8       ./.git/objects/fa
8       ./.git/objects/1e
12      ./.git/objects/df
8       ./.git/objects/0d
12      ./.git/objects/c4
4       ./.git/objects/info
16      ./.git/objects/pack
8       ./.git/objects/89
8       ./.git/objects/aa
12      ./.git/objects/ff
8       ./.git/objects/6a
108     ./.git/objects
8       ./.git/logs/refs/heads
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
28      ./.git/logs/refs
36      ./.git/logs
300     ./.git
324     .
```

5. Run the command **ls** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ ls
README.md
```

6. Run the command **ls -asl** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ ls -asl
total 32
 4 drwxrwxrwx+ 3 codespace root  4096 Jan 31 08:09 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jan 31 08:09 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jan 31 08:27 .git
20 -rw-rw-rw-  1 codespace root 17205 Jan 31 08:29 README.md
```

7. Run the command **free -h** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.8Gi       200Mi        70Mi       5.7Gi       5.5Gi
Swap:            0B          0B          0B
```

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 2990.744
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3013.127
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```

9. Run the command **top** and type **q** to quit. ***(1 mark)*** 
```bash
processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
top - 08:33:04 up 27 min,  0 users,  load average: 0.68, 0.40, 0.48
Tasks:  24 total,   1 running,  23 sleeping,   0 stopped,   0 zombie
%Cpu(s):  2.8 us,  3.0 sy,  0.0 ni, 94.0 id,  0.2 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    202.0 free,   1890.1 used,   5837.5 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   5661.1 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                                                               
   8527 codespa+  20   0   41.5g 335428  50432 S   1.3   4.1   0:25.64 node                                                                                                                                  
   2589 codespa+  20   0   41.5g 336492  50432 S   1.0   4.1   0:25.62 node                                                                                                                                  
   2524 codespa+  20   0   11.3g 129964  46848 S   0.3   1.6   0:10.99 node                                                                                                                                  
   3043 codespa+  20   0   11.1g  66044  44160 S   0.3   0.8   0:01.82 node                                                                                                                                  
      1 codespa+  20   0    1136    512    512 S   0.0   0.0   0:00.05 docker-init                                                                                                                           
      7 codespa+  20   0    7236   1792   1792 S   0.0   0.0   0:00.01 sleep                                                                                                                                 
     48 root      20   0   12196   3480   2560 S   0.0   0.0   0:00.00 sshd                                                                                                                                  
    987 root      20   0 1983260  76728  52480 S   0.0   0.9   0:00.18 dockerd                                                                                                                               
    994 root      20   0 1798848  47696  30464 S   0.0   0.6   0:00.84 containerd                                                                                                                            
   2344 codespa+  20   0    2616   1408   1408 S   0.0   0.0   0:00.01 sh                                                                                                                                    
   2374 root      20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                                                                                                                    
   2515 codespa+  20   0    2624   1536   1536 S   0.0   0.0   0:00.01 sh                                                                                                                                    
   2603 codespa+  20   0   11.2g  60448  43264 S   0.0   0.7   0:00.31 node                                                                                                                                  
   3054 codespa+  20   0 1007236  73336  41344 S   0.0   0.9   0:01.79 node                                                                                                                                  
   3950 codespa+  20   0    2616   1536   1536 S   0.0   0.0   0:00.01 sh                                                                                                                                    
   4001 root      20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                                    
   4235 codespa+  20   0   16812  11776   3456 S   0.0   0.1   0:00.20 bash                                                                                                                                  
   8265 codespa+  20   0    2616   1664   1664 S   0.0   0.0   0:00.01 sh                                                                                                                                    
   8307 root      20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                                    
   8538 codespa+  20   0   11.2g  58336  43392 S   0.0   0.7   0:00.25 node 
```

10. Run the command **uname -a**. ***(1 mark)*** 
```bash
@zamudun ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-f766f7 6.5.0-1025-azure #26~22.04.1-Ubuntu SMP Thu Jul 11 22:33:04 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```

11. What is the available free memory in the system. 
```bash
200MB
```

12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
```bash
20GB
```

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)***
```bash
22.04.1 Ubuntu x86_64
```
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
```bash
ls only shows the files and directory.
ls -asl shows all files including hidden, the sizes of each files in block and detailed information.
```

15. What is the TLB size of the Virtual CPU. ***(1 mark)***
```bash
2560 4K pages
```

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 
```bash
2855.748Mhz
```

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
```bash
PID 8527
```

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)***  

No, because the files is gone when you stop the container.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** 

Yes same like using the containers.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** 

The file are created with codespace:codespace as the user and group on the host virtual machine

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
Using sudo and chown command does succesfully changes its permission as shown using ls -1 command

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 
  Owned by user:root, group:root
2. What port is the apache web server running. ***(1 mark)***
  80
3. What port is open for http protocol on the host machine? ***(1 mark)*** 
  8080

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** 
  BusyBox is a lightweight Linux utility that provides essential Unix commands in a single binary. The --name flag assigns a custom name to a Docker container.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** 
NETWORK ID     NAME      DRIVER    SCOPE
0076c8a8a7e7   bluenet   bridge    local
6b912d08b54a   bridge    bridge    local
1ec4bc882fb4   host      host      local
82507c3b9923   none      null      local
1110a59609eb   rednet    bridge    local
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** 
  bluenet : 172.18.0.1
  rednet : 172.19.0.1
4. What is the network address for the running container c1 and c2? ***(1 mark)***
  bluenet : 172.18.0.2
  rednet : 172.19.0.2
5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** 
  no.
  The output: ping: bad address 'c2'

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** 
  yes.
  PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.125 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.062 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.067 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=6 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=7 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=8 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=9 ttl=64 time=0.088 ms
64 bytes from 172.20.0.3: seq=10 ttl=64 time=0.057 ms
64 bytes from 172.20.0.3: seq=11 ttl=64 time=0.071 ms
64 bytes from 172.20.0.3: seq=12 ttl=64 time=0.073 ms
64 bytes from 172.20.0.3: seq=13 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=14 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=15 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=16 ttl=64 time=0.068 ms
64 bytes from 172.20.0.3: seq=17 ttl=64 time=0.063 ms
64 bytes from 172.20.0.3: seq=18 ttl=64 time=0.068 ms
64 bytes from 172.20.0.3: seq=19 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=20 ttl=64 time=0.068 ms
64 bytes from 172.20.0.3: seq=21 ttl=64 time=0.085 ms
64 bytes from 172.20.0.3: seq=22 ttl=64 time=0.080 ms
64 bytes from 172.20.0.3: seq=23 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=24 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=25 ttl=64 time=0.074 ms
64 bytes from 172.20.0.3: seq=26 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=27 ttl=64 time=0.085 ms
64 bytes from 172.20.0.3: seq=28 ttl=64 time=0.071 ms
64 bytes from 172.20.0.3: seq=29 ttl=64 time=0.068 ms
64 bytes from 172.20.0.3: seq=30 ttl=64 time=0.086 ms
64 bytes from 172.20.0.3: seq=31 ttl=64 time=0.073 ms
64 bytes from 172.20.0.3: seq=32 ttl=64 time=0.062 ms
64 bytes from 172.20.0.3: seq=33 ttl=64 time=0.085 ms
64 bytes from 172.20.0.3: seq=34 ttl=64 time=0.077 ms
64 bytes from 172.20.0.3: seq=35 ttl=64 time=0.082 ms
64 bytes from 172.20.0.3: seq=36 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=37 ttl=64 time=0.078 ms
64 bytes from 172.20.0.3: seq=38 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=39 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=40 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=41 ttl=64 time=0.124 ms
64 bytes from 172.20.0.3: seq=42 ttl=64 time=0.073 ms
64 bytes from 172.20.0.3: seq=43 ttl=64 time=0.091 ms
64 bytes from 172.20.0.3: seq=44 ttl=64 time=0.082 ms
64 bytes from 172.20.0.3: seq=45 ttl=64 time=0.083 ms
64 bytes from 172.20.0.3: seq=46 ttl=64 time=0.057 ms

2. What is different from the previous ping in the section above? ***(1 mark)*** 
Previously, c1 and c2 were in separate networks (bluenet and rednet), so they couldn't communicate.
Now, they are both connected to an additional shared network (bridgenet), allowing communication.

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** __Fill answer here__.
2. Show the instruction needed to make this work. ***(1 mark)*** __Fill answer here__.



## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
