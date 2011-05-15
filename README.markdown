#Modified 3DSP driver source

I tried to compile the 3DSP source available at [3DSP official page](http://www.3dsp.com.cn), but it didn't work with Ubuntu 11.04, so I made some changes in the code and it works :)

First, you should install all dependencies:

    $ sudo aptitude install build-essential linux-headers-`uname -r`

With all dependencies satisfied, just clone this git repository and run Install\_3DSP.sh:

    $ git clone http://github.com/reyiyo/3dsp.git
    $ cd 3dsp
    $ sudo bash Install_3DSPUSB.sh

If you don't use git, just download the source from Github, extract it and run Install\_3DSP.sh:

    $ curl http://github.com/reyiyo/3dsp/tarball/master -o 3dsp.tar.gz
    $ tar -xvzf 3dsp.tar.gz
    $ cd 3dsp
    $ sudo bash Install_3DSP.sh

If you are using Ubuntu with Unity desktop, the uWB and Wifi Radar icon will not appear in the systray. You will have to do one aditional step, that you can find it here:

(In spanish): http://tuamigotetieneganas.blogspot.com/2011/04/unity-area-de-notificacion-systray.html

If you have any question, contact me: reyiyo [at] gmail [dot] net

