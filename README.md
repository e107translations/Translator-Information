
## Language.xml

When contributing, please make sure you edit `e107_languages/YourLanguage/YourLanguage.xml` so that it contains the version of e107 the language-pack has been translated for and the date you made your last edit. 

eg. If you were updating the Spanish pack for e107 v2.1.2, in `e107_languages/Spanish/Spanish.xml` you would modify ***compatibility*** and ***date*** (YYYY-MM-DD) to look like this: 

`<e107Language name="Spanish" compatibility="2.1.2" date="2016-10-28" >`


## Publishing Official Language Packs

After e107 has officially released a new version, and your language files are up-to-date, you may release/publish your pack via the ***Releases*** area on Github. 

### Steps:

1. Make sure your repo is up-to-date and the .xml file contains the ***correct version*** and date. 
2. Go to the "releases' area. eg. https://github.com/e107translations/YOUR-LANGUAGE/releases
3. Click ***Create a new release***
4. Enter for `Tag version` the current version. eg. ***v2.1.5*** (make sure you include the ***v*** )
5. Enter for `Release title` the name of your pack. eg. ***e107 German Language Pack***
6. Enter a description (optional)
7. Click ***Publish release***

Zip files will be automatically created. 

## Publishing a Pre-Release Language Pack (optional) 

If you wish to publish a language-pack for a 'yet to be released' version of e107. eg. ***2.1.6 (git)*** or any other version containing ***(git)*** please follow the steps above but check the box ***pre-release*** prior to step 7. 



## The Translation Process

### Setup
1. Clone the repo to your local hard disk. eg. ```git clone https://github.com/e107translations/YOUR-LANGUAGE.git``` 
2. Install the official release of e107 in a different folder or on a remote server. 
3. Copy and Paste all the files (except .git) from your repo folder over the top of your e107 folder. When done correctly you will find  ***YOUR-LANGUAGE*** folder and an ***English*** folder inside ***e107_languages/***  

### Translating the Files
1. Translate your language files via ``` Admin > Language > Language-Packs > Verify > Edit ```
2. Correct all errors (check any warnings)
3. When you feel it is complete, generate a new language-pack .zip using "Generate Pack" in ``` Admin > Language > Language-Packs ``` of e107

### Updating the Repo
1. Unzip the newly generated .zip file over the top of your cloned repo. 
2. Check that the folder/file structure is correct with ***e107_languages*** in the root. 
3. Commit your changes using your git client. 
4. Push the changes to Github using your git client. 


## FAQS

Q. I have a v1.x language pack I would like to upgrade. What do I do?

A. Unzip the v1.x language pack into v2.x and then follow the procedue above: ***Translating the Files***
