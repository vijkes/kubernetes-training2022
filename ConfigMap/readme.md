kubectl create configmap newcm2 --from-file newcm2.conf

=======================================================================


configmap is a way to make your config centralised
the changed made here will be permanent	
A ConfigMap stores configuration settings for your code.

PVC: to make entire folder permanent
ConfigMap: to make configuration file permanent
Env/Secret: to make any env var permanent
