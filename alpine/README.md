# based on alpine but with the following packages installed

package | version (latest if blank) 
------- | -------------------------
bash |  
jq| |  
wget | 

*note to run bash, if an entry poiint is defined you need to run 'docker run -it --entrypoint /bin/bash <image>'*
  
 

A Kubernetes secrets is required for this example

kubectl create secret docker-registry docker-credentials \
    --docker-username=<username>  \
    --docker-password=<password> \
    --docker-email=<email-address>
