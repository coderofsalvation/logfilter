logfilter
=========

easy portable bashscript to monitor syslog- and logfile events with on-the-fly filtering and highlight features

### Usage

    ./logfilter /var/log/syslog

### The problem

'tail -f' is nice to monitor logfiles, but its far from ideal.
Especially when dealing with large volumes of data.
Logfilter prevents you from going crazy with bashoneliners to get some sensible output.

Basically you will be going from this:

  <img alt="tail -f alternative" src="https://raw.githubusercontent.com/coderofsalvation/logfilter/master/.res/tailf.png"/>

To this:
  
  <img alt="logfilter is a tail -f alternative" src="https://raw.githubusercontent.com/coderofsalvation/logfilter/master/.res/logfilter.png"/>

### On the fly comfort

This portable utility was written to overcome the repetitiveness of fiddling with grep and tail -f.
Logfilter is a wrapper for 'tail -f' and grep.

### Filtering incoming data

At any time you can press CTRL-C and modify your incoming regex:

  <img alt="logfilter is a tail -f alternative" src="https://raw.githubusercontent.com/coderofsalvation/logfilter/master/.res/filterin.png"/>

### Filtering outgoing data

Too much data to stdout? At any time you can press CTRL-C and modify your outgoing regex:

  <img alt="logfilter is a tail -f alternative" src="https://raw.githubusercontent.com/coderofsalvation/logfilter/master/.res/filterout.png"/>

### Highlighting data

Want to have warnings/errors to standout? Press CTRL-C and modify your highlighting regex:
  
  <img alt="logfilter is a tail -f alternative" src="https://raw.githubusercontent.com/coderofsalvation/logfilter/master/.res/filterout.png"/>
