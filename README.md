# Generating self-signed CA certificates
A UNIX shell script for quickly deploying a self-signed CA, and generating the self-signed certificates from it.

# How to run
<br>After downloading the script, run the following command to assign necessary previliges for running the script. </br>
'sudo chmod 777 certGen.sh'

Then run './certGen.sh node1.foo. node2.foo.'
Here 'node1.foo' and 'node2.foo' are the nodes needing the self-signed CA certificates.
