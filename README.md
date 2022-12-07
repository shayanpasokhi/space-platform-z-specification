# space-platform-z-specification
z specification for a space platform

doc:
[space-platform-z-specification.pdf](https://github.com/shayanpasokhi/space-platform-z-specification/files/10174455/space-platform-z-specification.pdf)

A space platform contains a number of instruments. Several
communications channels are provided allowing both input and
output instrument communications. Platform instruments may be
placed in active or inactive states. Only active instruments may be
assigned to I/O-channels. Active instruments may be assigned to
more than one I/O-channel, up to some maximum number of
I/O-channels per instrument. Further, I/O-channels may be shared
by several active instruments, up to some maximum number of
instruments shared per I/O-channel.

The objective is to construct a specification, that will
manage the assignment of communication I/O-channels to
spacecraft platform instruments.

![image](https://user-images.githubusercontent.com/81962498/206135626-02719bc2-997c-4e24-906a-a7707af49019.png)
