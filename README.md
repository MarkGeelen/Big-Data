## File Transfer
### CSV Files: Melbourne water use by postcode: 
https://www.data.vic.gov.au/data/dataset/38f43f13-d988-419a-8e99-39ff6c41e5f2/resource/00378584-3157-42f7-9370-a8f0e71ecfc1/download/.fileswateruse.csv

     wget link -O file_name


### Zip Files: Taxation Statistics 1994-95 to 2008-09: 
https://data.gov.au/dataset/67265383-0ecc-4523-8ffd-02790297a65a/resource/2f236165-69a4-4d6a-9da6-5b39bfa70737/download/taxstats-1994-95-to-2008-09.zip 

     wget zip_link -O file_name
     unzip file_name -d folder_name


### Gist Snippets: https://gist.github.com/borhan-kazimipour
     As a single file:   wget raw_link -O file_name
     All files:          git clone https_link folder_name

### Git Repositories:  https://github.com/onurakpolat/awesome-bigdata

     git clone https_link folder_name

### Local Files:
Find the IP of MoVE: In MoVE terminal:
 
     hostname -I
     
Transfer the local file from your machine to MoVE: In local terminal: 

     scp file_name user_name@MoVE_IP_address:destination_folder
     
Transfer the file from MoVE to BigVM; In MoVE terminal: 

     scp file_name BigVM_IP_address:destination_folder
