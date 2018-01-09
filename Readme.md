

# How to work on github and adding protocols

1. open github and click on Hahn lab protocols, press sync to update the project from the internet to your local computer
2. right click on Hahn lab protocols and click on "Open in finder" or "open in explorer"
3. Double click the "Hahn_lab_protocols.Rproj" to open up R studio
4. make any changes to the a protocol file with ".Rmd" extension by adding text and make sure you KNIT to HTML  and save
5. changes will stage in github desktop
6. commit changes and sync


# Constructing protocols

Work off of this example [template](https://adnguyen.github.io/Hahn_lab_protocols/Protocol_template.html) (Protocol_template.Rmd). 

1. Basically, copy and paste "Protocol_template.Rmd" in the "Hahn_lab_protocols" folder. 
2. Rename the file in following format:
   1. "Date_initials_informative_protocol_name.Rmd"
   2. example- "2018-01-09_AN_qpcr_protocol.Rmd"
   3. Notice that the date is in (YYYY-MM-DD format)
3. Open it up in Rstudio
4. Fill in the title, your name, and date (YYYY-MM-DD format please)
5. Fill in the general information and notes that the reader needs to know before starting 
6. List reagents and provide the vendor and catalog number and URL link
   1. ex: [RNesy Mini Kit (50)](https://www.qiagen.com/us/shop/sample-technologies/rna/total-rna/rneasy-mini-kit/#orderinginformation) (vendor- Qiagen, cat # 74104)
7. Fill in protocol with a series of steps 
