# FUES_EGM
EGM using fast upper-envelope scan.


Initial beta replication material for `Fast upper-envelope scan for discrete-continuous dynamic programming' by Dobrescu and Shanker (2022). 

Please see the top-level code for ```retirement.py``` and ```fella.py``` for exmaple use of Euler iteration and VFI for the retirement and discrete grid housing model.

Consumption policy function generated using Ishkakov et al (2017) params and no smoothing. 
![ret_cons_all](https://user-images.githubusercontent.com/8477783/181183127-4bf48f5b-8280-4f9f-afe1-1730894c0e29.png)

Upper envelope generation using FUES and Ishkakov et al (2017) params. 
![ret_vf_aprime_all_17](https://user-images.githubusercontent.com/8477783/181172326-d36527a3-411a-4ba0-bff7-1528d1d368d8.png)

Upper envelope and policy functions for Ishkakov et al (2017) params and smoothing param = 0.05. 
![ret_vf_aprime_all_17_sigma](https://user-images.githubusercontent.com/8477783/181172404-1b0bbb74-5c40-47c0-aff9-0d34b573f7f2.png)

![ret_cons_all_sigma](https://user-images.githubusercontent.com/8477783/181172415-72f866b9-348e-4de9-9855-fb509591deb2.png)
