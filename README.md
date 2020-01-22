

![Lyée notre Dame](http://www.lyceenotre-dame72.fr/local/cache-vignettes/L200xH135/siteon0-edfa2.jpg)
### Contexte et historique de HTML
    Le langage HTML (Hyper Text Markup Language) fait partie d’une classe plus vaste de langages (SGML, XML, XHTML,...)
    destinés à décrire des documents et leur mise en page tout en distinguant la forme et le fond.
    Il a été inventé Tim Berners-Lee en 1991 et a d’abord été utilisé par des physiciens du CERN afin de communiquer leurs travaux.
    Il est a la base du WEB, la partie actuellement la plus utilisée d’internet.

    Tim Berners-Lee suit encore aujourd'hui avec attention l'évolution du Web 
    et a créé le World Wide Web Consortium (W3C) qui définit les nouvelles versions des langages.
    Il a par ailleurs créé plus récemment la World Wide Web Foundation, qui analyse et suit l'évolution du Web.


### la base

    créer un repertoire *monsite* dans *Bureau*
    Créer le fichier *moncv.html* dans le répertoire *Bureau/monsite/*
    Télécharger l'image depuis :
 [image](https://raw.githubusercontent.com/Nounem/NSI/master/photo.png) 

```html
<html>
    <head>
         <meta name="author" content="Marc Glisse">
         <!-- je suis bête, j'ai oublié de modifier le nom de l'auteur -->
         <title>
                Premier essai
          </title>
    </head>
    <body>
             <p>
              Bonjour tout le monde...
             </p>
     <!-- je ne sais pas trop quoi écrire alors je fais plein de commentaires qui ne vont pas s'afficher -->
            <hr>
    </body>
</html>
````

### les titres et paragraphe


 ```html
<h1>Voici un titre</h1>  
<h2>Maintenant un sous-titre</h2>  
<h3>Et on peut continuer</h3>  
<h4>La profondeur est limitée</h4> 
<h5>Pénultième</h5>  
<p>Un petit texte justifié à droite pour introduire  cette partie, elle le mérite bien, et puis il serait dommage de se  priver. </p> 
<h6>Un vraiment petit paragraphe</h6>  
<p> Et un titre est un changement de paragraphe implicite.</p> 

````

### les listes

```html 
<H1>Les mois du printemps</H1>
    <UL>
        <LI>avril
        <LI>mai
        <LI>juin
    </UL>
    <P>
    <H3>Les mois d'automne</H3>
        
    <OL>
        <LI>octobre
        <LI>novembre
        <LI>decembre
    </OL>
            
            
            
     <ul>   
            <li> <b> Le texte peut être en gras, </b> </li> 
            <li> <em> Les italiques mettent le texte en valeur ! </em> </li>   
            <li> Et enfin, on peut écrire à la machine du même nom, </li>     
            <li> un style souligné à éviter : ici, on ne peut pas cliquer,</li>   
            <li> et on peut même rayer du texte  </li>  
            <li> <big> On peut écrire de gros caractères, </big> <small> ou de petits </small> </li>     
            <li> Et enfin, on peut utiliser des exposants comme dans 1<sup>er</sup> ou des indices, u<sub>n+1</sub> = u<sub>n</sub>+1                </li>   
    </ul>  
    <ul>   
        <li> Du texte violet, </li>  
       <li> du texte, du texte plus gros (en relatif), </li>   
       <li> du texte, taille absolue,  </li>     
       <li>  et des jolies lettres.</li>  
    </ul>  
````

 ### les tableaux
  
  
  



 *exemple 1*
  ```html 
<TABLE BORDER>
     <CAPTION ALIGN=top> PREMIER TABLEAU</CAPTION>
       <TR>
         <TD>ligne 1 ; cellule 1</TD>
         <TD>ligne 1 ; cellule 2</TD>
       </TR>
       <TR>
         <TD>ligne 2 ; cellule 1</TD>
         <TD>ligne 2 ; cellule 2</TD>
       </TR>
 </TABLE>
 
````
 *exemple 2*
 
  ```html
 <TABLE BORDER=8 CELLPADDING=10>
         <CAPTION>DEUXIEME TABLEAU </CAPTION>
         <TR>
              <TH COLSPAN=5>LETTRES</TH>
         </TR>
         <TR>
             <TD>Aa</TD>
             <TD>Bb</TD>
             <TD>Cc</TD>
             <TD>Dd</TD>
             <TD>Ee</TD>
         </TR>
         <TR>
              <TD>Ff</TD>
              <TD>Gg</TD>
              <TD>Hh</TD>
              <TD>Ii</TD>
              <TD>Jj</TD>
         </TR>
 </TABLE>
 

````



### les liens et les images



*les liens*
```html
<a href="exemple.html">Lien vers le fichier « exemple.html » se trouvant dans le même répertoire que la
page actuelle</a>

<a href="repertoire_exemple/exemple.html">Lien vers le fichier « exemple.html » se trouvant dans le
répertoire « repertoire_exemple » qui se trouve dans le même répertoire que la page actuelle</a>
````
*les images*
```html
<IMG SRC="Adresse de l'image"> 
    
<A HREF="fichier.htm"><IMG SRC="image.gif"></A>

````



## EXERCICE 1 : creer un CV

* Insérer l'image dans la page Web à l'aide de la balise `<img>`

* Ajouter le *Nom* et *Prenom* dans une balise de `<h1>`
   * l'âge dans un paragraphe 
   * le métier dans un autre paragraphe
   * l'adresse dans un unique environnement
* Ajouter la partie Formation en utilisant un environnement `<H1>` contenant le titre Formation comme titre de premier niveau.

##Help

Having trouble with Pages? Check out our [documentation](http://www.lyceenotre-dame72.fr/local/cache-gd2/67168535ab900a80834ab76344a73b3d.jpg) 
