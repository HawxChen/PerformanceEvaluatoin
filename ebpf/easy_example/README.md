### EBPF usage example for java programs

* Tools should be install.
    * bcc-tools
    * strace.ebpf
* How to use
    * javac HelloWorld.java
    * HelloWorld.class should be generated.
    * ./strace.ebf -f -o output.log java HelloWorld
