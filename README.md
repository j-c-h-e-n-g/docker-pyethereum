docker-pyethereum
-----------------

In an ideal world you'd just install things and they would work! I have 
suffered for you, the internet. The hordes of folks who want ot install 
pyethereum!

Basically this installs dependecies needed to run the python 
implementation of ethereum.

You should see this output if you run `python2.7 /tmppyethereum/eth.py`:

    bash-4.1# python2.7 pyethereum/eth.py
    Bottle v0.12.7 server starting up (using WaitressServer())...
    Listening on http://127.0.0.1:30203/
    Hit Ctrl-C to quit.
    
    serving on http://127.0.0.1:30203


Dependencies
------------

pyethereum ships with a `requirements.txt` which you can point pip at
in order to install python module dependencies.

* Python-2.7.6
* pip2.7
