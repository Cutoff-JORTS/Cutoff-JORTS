 alias @Cutoff-JORTS='jort'
Self-taught Linux admin. I pivoted from a 10-year career in banking to pursue work that more deeply excites me. Administrator of my home-lab, which includes local SMB fileshare, automated backup storage for 4x local machines, personal cloud storage, private media server, and VM host (for a Folding @ Home machine, working specifically on organizing Alzheimer's-related datasets for ongoing medical research).

Keep up with me here: https://jorts.tech where I post project updates, scripts for Bash & Powershell (with links to available public GitHub repos), and a weekly news-bite piece called "Buzzwords of the Day"
- How to reach me: https://jorts.tech/contact

      hardware: Ryzen 3700x (8c/16t) || 64GB RAM || Radeon R9 270 || headless || maximum power draw=275W
       > Contained VM - runs Fold @ Home full-time inside Win10 environment {
            dedicated_cores=6
              utilization_limit=80%
            dedicated_ram=8GB
         }
       > 8TB ZFS Pool (mirror) - acts as local file server for clients on home network {
            Secure & redundant storage for my personal hobby photography projects, film & TV collection, and any crucial files
             Includes networked storage of all notes for several Dungeons & Dragons campaigns
           #Most of my learning scripts are oriented around manipulating this dataset
         }
       > Docker Containers {
         nginx - SSL protected reverse proxy
         Nextcloud - Private cloud storage
         }
       > Jellyfin - hosted media server avialable over https via self-signed SSL cert 
