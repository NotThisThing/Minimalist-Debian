# Minimalist-Debian
The goal of this project is to make the minimal Debian core ready to use

## What is Debian Minimalist Core?
Debian Minimalist Core is a barebones Linux distribution based on Debian that prioritizes the terminal interface.

## Where can I download it?
Download link: http://u.pc.cd/hGActalK 

## Log
* 2023-03-31
  * Debian minimalist core v.0.01b released (file sha256: c8a0674966d4df1894e1c184c54293c9ae7a7dabe956a8688dd9ad0954f54577)
    * VM: VMWare Workstation 17 Player
    * Spec:
      * RAM: 2GB
      * Core: 1
      * Space: 80GB 
      * Based: Debian 11 Bullseye
    * | user | pass | description |
      |------|------|-------------|
      | root | toor | admin user account |
      | debian | debian | user account |
    * installed packages for user `debian`:
      * sudo, openssh, neofetch
      * zsh, oh-my-zsh, powerlevel10k, zsh-syntax-highlighting, zsh-autosuggestions
  * Debian minimalist LEMP v.0.01b released (file sha256: 20e51b575e0543c9e4793db14ded9c68b3cb4e186c568e6ce76b76905a402db2)
    * VM: VMWare Workstation 17 Player
    * Spec:
      * RAM: 2GB
      * Core: 1
      * Space: 80GB 
      * Based: Debian 11 Bullseye
    * | user | pass | description |
      |------|------|-------------|
      | root | toor | admin user account |
      | debian | debian | user account |
    * installed packages for user `debian`:
      * sudo, openssh, ufw, neofetch
      * zsh, oh-my-zsh, powerlevel10k, zsh-syntax-highlighting, zsh-autosuggestions
    * LEMP:
      * Nginx 1.18.0
      * MariaDB ver.15.1 Distrib 10.5.18-MariaDB
        * Admin User: `root`
        * Admin Pass: `toor`
      * PHP 7.4.33 (CLI)
      * web folder location: `/var/www/html/`
