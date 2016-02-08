# OpenSeesAPI
OSAPI short for OpenSeesAPI is a python package that is used to write [OpenSees](opensees.berkeley.edu) tcl scripts quickly.
OSAPI is written using an object-oriented programing style making easy to interact with other commonly used python packages like numpy, scipy and maptlotlib.


## Installation instructions

- Make sure you have OpenSees [downloaded](http://opensees.berkeley.edu/OpenSees/user/download.php) and installed (including the required TCL libraries).
- Add OpenSees or OpenSeesSP/OpenSeesMP to your system path. This can be done easily in the command windows or terminal (mac users).

Windows Users:

<pre><code>set PATH=%PATH%;OpenSeesExeutableLocation
</code></pre>

Mac/Linux Users:

<pre><code>export PATH=$PATH:~/OpenSeesExecutableLocation
</code></pre>

- Install OpenSeesAPI using pip. This can be done using the following command.

<pre><code>pip install OpenSeesAPI
</code></pre>

## Example Scripts

Three Example Script using this OpenSees Wrapper have been posted:
- SampleScript1.py => SDOF System with a Deteriorating Ibarra Spring
- SampleScript2.py => 40 Story PEER - Tall Building Initiative Building with Buckling Restrained Braced Frames
- SampleScript3.py => Moment Curvature analysis for a concrete column

I am working on more. Email me if you have suggestions or need something specific.