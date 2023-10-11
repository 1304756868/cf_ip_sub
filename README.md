# cf_ip_sub
An automated program that is designed to perform daily testing and filtering of CF better IP addresses, updating into the subscribed links. Manual testing and filtering of CF better IP are no longer necessary. Simply update the subscription in Clash or V2RayN when needed.

**vlwoker.yaml**   
Better IPs will be updating into this file daily. When the CF worker is invoked, it will read the content from here.

**nas**   
Program running in your nas or linux PC, performing daily testing and filtering of CF better IP addresses, updating them into "vlwoker.yaml" in this git.

**cf-worker**   
The code filled in the CF worker.   
After deployment, subscribe through the following two links:
- clash:  
  https://<your_cf_worker_domain>/sub?servername=<your_vless_worker_domain>&type=clash&uuid=<your_uuid>
- v2rayn:  
  https://<your_cf_worker_domain>/sub?servername=<your_vless_worker_domain>&type=urls&uuid=<your_uuid>
