# VPNClientPulse

In RHEL/CentOS/Fedora, "/etc/pki/tls/certs/ca-bundle.crt" is used as CA certificate store.


In Ubuntu, "/etc/ssl/certs/ca-certificates.crt" is used as CA certificate store.


Also do not forget to set the library paths:

export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/pulse




For getting the package that works on Open Suse (verified), Google Chrome Linux OS (verified) unzip the file loaded via github lfs, it contains the unpackaged code with required library so files that you have to move to system install folders (/usr/lib for many systems)
