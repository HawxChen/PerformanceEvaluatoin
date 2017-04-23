###EBPF usage example for java programs

* Environment
    * bcc-tools
    * strace.ebpf

* How to use
    * javac HelloWorld.java
    * HelloWorld
    * ./strace.ebf -f -o output.log java HelloWorld
