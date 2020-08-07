# JSTL-internationalization-Form-i18n-
Simple Multi-lingual Registeration Form using JSTL , HTML , CSS , Bootstrap

## how to use it ?
* clone the repository
* make a java dynamic website(if you use eclipce) or java enterprise --> web application  (if you use intellij)
* import the libraries from web/WEB-INF/libs path in your project
* set the configurations for localhost (tomcat server)

## how to add more languages ?
* make a .properties file in the package src/com/resources with the name (label_languageCode_CountryCode.properties) for ex:label_en_UK.properties (for UK english)
* add anchor to index.jsp   
```
  <a href ="index.jsp?theLocale=languageCode_CountryCode"> <img src="your_country_flag"> </a>
```
for ex :
```
  <a href="index.jsp?theLocale=fr_FR"><img src="images/001-france.png" alt="france" title="FR"></a>
```

![english page](https://github.com/EngAhmedSalah/JSTL-internationalization-Form-i18n-/blob/master/images/english.PNG)
