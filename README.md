# Translator-Information


## Language.xml

When contributing, please make sure you edit `e107_languages/YourLanguage/YourLanguage.xml` so that it contains the version of e107 the language-pack has been translated for and the date you made your last edit. 

eg. If you were updating the Spanish pack for e107 v2.1.2, in e107_languages/Spanish/Spanish.xml you would modify ***compatibility*** and ***date*** (YYYY-MM-DD) to look like this: 

`<e107Language name="Spanish" compatibility="2.1.2" date="2016-10-28" >`


## Publishing Releases

After e107 has officially released a new version, and your language files are up-to-date, you may release/publish your pack via the ***Releases*** area on Github. 

### Steps:

1. Make sure your repo is up-to-date and the .xml file contains the correct version and date. 
2. Go to the "releases' area. eg. https://github.com/e107translations/YOUR-LANGUAGE/releases
3. Click ***Create a new release***
4. Enter for `Tag version` the current version. eg. ***v2.1.5*** (make sure you include the ***v*** )
5. Enter for `Release title` the name of your pack. eg. ***e107 German Language Pack***
6. Enter a description (optional)
7. Click ***Publish release***

Zip files will be automatically created. 
