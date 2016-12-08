## Guidelines for Kickstarts

 * Kickstarts should provide comments explaining actions in each section
 * Kickstarts should end in .cfg or .ks
 * Kickstart names should provide a version and brief description, for example
   `redhat7.cfg` or `redhat7-workstation.ks`


Detail of my setup 

        OS = Red Hat 7.3
        Memomy = 1 GB
        Total Disk = 20 GB
        
        Boot
        boot = 200 MB
       
        Total size vg_sys = 10 GB (10240 MB)
        lv_root 9 GB (9216 MB)
        lv_swap 1 GB (1024 MB)

        Total size vg_apps 9.8 GB (10032 MB)
        lv_var 9.8 GB (10032 MB)


Logical volume mounted 

        lv_root mounted to /
        lv_swap mounted to swap
        lv_var mounted to /var


Link to my kickstart video

        https://youtu.be/debzw0nCMBk
