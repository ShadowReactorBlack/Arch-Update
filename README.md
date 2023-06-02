# Arch-Update
a small Bash script to update the system and update the mirrorlists

### How To install:
## 1. Clone This Repository by Running
   ` git clone https://github.com/ShadowReactorBlack/Arch-Update `
## 2. After Cloning Install Dependencies
   ` sudo pacman -Syyu reflector rsync curl flatpak`
## 3. Cd Into The Directory
      ` cd Arch-Update `
## 4. Place The Files In The /usr/local/bin Directory      
   - ` cp arch-update-dracut /usr/local/bin ` For Darcut Users
   - ` cp arch-update-mkinitrd /usr/local/bin/ ` For Mkintrd Users
- Done You Are All Finished Installing

# To Start Just Execute
- ` arch-update-dracut ` To Start For Dracut Users 
- `arch-upadte-mkinitrd` To Start For mkinitrd Users 
