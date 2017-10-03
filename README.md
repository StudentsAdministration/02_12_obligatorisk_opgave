# Obligatorisk Opgave 2. semester Softwarekonstruktion dat17v1

Tirdag d. 3-10-2017 til d. 10-10-2017   
Opgaven laves i Grupper    
Aflevering på Fronter senest mandag d. 9-10-2017 kl 16.00.   
Fremlæggelse i klassen tirsdag d. 10-10 kl. 8.30 - 11.45.
 
I  denne obligatoriske opgave skal i lave en del af et website, nemlig det at man som bruger kan oprette en konto og at man kan logge ind med brugernavn og password og derved komme ind til ellers ikke tilgængelige sider på sitet.
Vi har været igennem det meste af det i skal bruge i denne opgave i undervisningen, men dog ikke alt. 

Opgaven skal løses i grupper, og i skal skrive alle gruppemedlemmers navne ind i dette google sheet:

**[Grupper til obligatorisk ogave 1](https://docs.google.com/spreadsheets/d/1JohXXTd2eufrPaeKrAbsRU7xlN6TM0hrTHhDZ0c0c_A/edit?usp=sharing)**

Når i er færdige med opgaven skal i på Fronter aflevere et link til et Github repository.
I skal desuden i 10 minutter på tirsdag d. 10-10 fortælle om og vise klassen jeres projekt.

Opgaven indeholder følgende Use Cases:

## Use Cases

* Create User
* Change Password
* Delete User
* Login

### UC #1: Create User
On the website a user must be able to create an account which takes the users name, 
the users address, the users email, and a desired password of the user. 
If you need to get inspired you can have a look at this [webpage](https://www.louis.de/mylouis/registrieren)    
Please create an account!!

### UC #2: Change Password
**Main Success scenario:**   
The user should be able to change his password by typing in the old password and the new password twice.  
If you need to get inspired you can have a look at this <a href="https://www.louis.de/mylouis/passwort-aendern"><img scr="https://github.com/dat17v1/02_12_obligatorisk_opgave/blob/master/img/changepassword.png" /></a>

**Alternative flow:**   
If the new passwords entered does not equal each other, the user should be propted to write in the passwords again.

### UC 3: Delete user
The user should be able to delete his account. In order to do so, the user should type in his password, and only if this is correct the users account should be deleted.

### UC #4: Login
The user should be able to login in order to see an extreemlysecret.html site. The extreemlysecret.html site should not be visible to users without an account.
 
## Formelle krav til opgaven
* I skal gøre brug af en Mysql Database i jeres projekt.
* I skal oprette et projekt vha Spring Boot Initializer.
* I skal demonstrere at i kan arbejde med MVC arkitekturen i en Spring Boot Applikation.


**Det med småt**    
Hvis denne opgave ikke afleveres, dvs. afleveres på fronter og vises for Claus, mister i et eksamensforsøg til 1 års eksamenen til jul.

