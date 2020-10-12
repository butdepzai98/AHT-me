How to set up :
- B1: git clone https://github.com/butdepzai98/AHT-me.git
- B2:
    Create Block by
    Insert Data in link to PhpMyAdmin
    https://drive.google.com/file/d/1S2QbCdGHQYDMKCUYdbfCMMz4tNbkepKR/view?usp=sharing 
    and
    https://drive.google.com/file/d/1ju6bmUEnG1E7h_HAxVo4RSfGrUrzGz9c/view?usp=sharing
    
- B3:
    Install Extendtions Megamenu
    https://drive.google.com/drive/folders/1piREG1ezucEW5YwPJYAz0eA7kx_mOvVp?usp=sharing
    
- B4: Run cmd
    sudo bin/magento setup:di:compile && sudo bin/magento setup:upgrade && sudo bin/magento s:s:d -f && sudo chmod -R 777 * && sudo bin/magento c:c
    
- B5: Active Megamenu and Import file setting
    Go to Admin -> VenusTheme -> Licenses
    Go to Admin -> VenusTheme -> Import -> Choose File : setting.json
    sudo bin/magento c:c
    
- B6:
    Go to Admin -> Content -> Configuration ->	Main Website -> Edit
    Choose AHT Me
    sudo bin/magento c:c
    
- B7:
    Setup Grunt
    sudo chmod -R 777 * && rm -rf var/cache var/page_cache var/view_preprocessed/frontend pub/static/frontend/AHT && sudo bin/magento s:s:d -f --theme AHT/me && sudo chmod -R 777 * && grunt clean:me && grunt exec:me && grunt less:me && sudo bin/magento c:c && sudo chmod -R 777 * 
    
