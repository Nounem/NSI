

![Lyée notre Dame](http://www.lyceenotre-dame72.fr/local/cache-vignettes/L200xH135/siteon0-edfa2.jpg)
### Contexte et historique de HTML
    Le langage HTML (Hyper Text Markup Language) fait partie d’une classe 
    plus vaste de langages (SGML, XML, XHTML,...) destinés à décrire
    des documents et leur mise en page tout en distinguant la forme et le fond.
    Il a été inventé Tim Berners-Lee en 1991 et a d’abord été utilisé 
    par des physiciens du CERN afin de communiquer leurs travaux.
    Il est a la base du WEB, la partie actuellement la plus utilisée d’internet.

    Tim Berners-Lee suit encore aujourd'hui avec attention l'évolution du Web 
    et a créé le World Wide Web Consortium (W3C) qui définit les nouvelles
    versions des langages. Il a par ailleurs créé plus récemment la World Wide Web Foundation,
    qui analyse et suit l'évolution du Web.


### la base

  
```html
<html>
    <head>
         <meta name="author" content="nom et prenom">
         <!-- je suis un commentaire -->
         <title>
                Premier essai
          </title>
    </head>
    <body>
             <p>
              Bonjour tout le monde...
             </p>
     
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
<h5>plus petit que h4</h5>  
<p>Un petit texte justifié à droite pour introduire  cette partie,
    elle le mérite bien, et puis il serait dommage de se  priver.
</p> 
<h6>Un vraiment petit paragraphe</h6>  
<p> Et un titre est un changement de paragraphe implicite.</p> 

````

### les listes

```html 
<H1>Les mois du printemps</H1>
    <UL>
        <LI>avril </LI>
        <LI>mai</LI>
        <LI>juin</LI>
    </UL>
    <P>
    <H3>Les mois d'automne</H3>
        
    <OL>
        <LI>octobre</LI>
        <LI>novembre</LI>
        <LI>decembre</LI>
    </OL>
            
            
            
     <ul>   
            <li> <b> Le texte peut être en gras, </b> </li> 
         
            <li> <em> Les italiques mettent le texte en valeur ! </em> </li>   
         
            <li> Et enfin, on peut écrire à la machine du même nom, </li>     
         
            <li> un style souligné à éviter : ici, on ne peut pas cliquer,</li>  
         
            <li> et on peut même rayer du texte  </li>  
         
            <li> <big> On peut écrire de gros caractères, </big> <small> ou de petits </small> </li>   
         
            <li> Et enfin, on peut utiliser des exposants comme dans 1<sup>er</sup>
                ou des indices, u<sub>n+1</sub> = u<sub>n</sub>+1        
            </li>   
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

* Créer un dossier *monsite* dans *vos documents personnels*
* Créer le fichier *moncv.html* dans le dossier *monsite*
* Télécharger l'image au lien ci-dessous :
 
 
 [Telecharger image ici ](https://raw.githubusercontent.com/Nounem/NSI/master/photo.png) 




* Insérer l'image dans la page Web à l'aide de la balise `<img>`

* Ajouter le *Nom* et *Prenom* dans une balise de `<h1>`
   * l'âge dans un paragraphe 
   * le métier dans un autre paragraphe
   * l'adresse dans un unique environnement
* Ajouter la partie Formation en utilisant un environnement `<H1>` contenant le titre Formation comme titre de premier niveau.

### Résultat


![Mon-cv](https://raw.githubusercontent.com/Nounem/NSI/master/cv.PNG)












# PARTIE 2 : CSS 

    *CSS* (Cascading Style Sheets : feuilles de style en cascade) est un langage informatique
    qui sert à décrire la présentation des documents HTML.
    L'un des objectifs majeurs des CSS est de permettre la mise en forme hors des documents.
    Il est par exemple possible de ne décrire que la structure d'un document en HTML,
    et de décrire toute la présentation dans une feuille de style CSS séparée.
    Ainsi, les avantages des feuilles de style sont multiples :
  * La structure du document et la présentation peuvent être 
    gérées dans des fichiers séparés.
    
  * La conception d'un document se fait dans un premier temps sans se soucier
  de la présentation, ce qui permet d'être plus efficace



## Lien entre la page HTML et la feuille de style CSS

    On peut relier une page web et un fichier CSS en utilisant la balise <link/> :
    
```html
<head>
    <link rel="stylesheet" href="Nom_du_fichier.css"/>
</head>
```

## Mise en forme de l'arriere plan

```html
<body>
</body>
    Pour ajouter du CSS dans la balise <body>
    body{
        background-color: green | red | yelow | ... ;
    }

```

## Mise en valeur du texte

<p>
    background-color: green | red | yelow | ... ;<br/>
    color: green | red | yelow | ...  ;<br/>
    font-family: arial, verdana , sans-serif ; <br/>
    font-style: normal | italic ; <br/>
    font-size: 50px ; <br/>
    font-weight: normal | bold ;<br/>
</p>



## Mise en forme du texte

<p>
    text-align: center | left | right | justify<br/>
    text-decolaration: underline | overline | 
</p>



<table>
  <tr>
    <th>Propriétes</th>
    <th style="background-color: yellow">valeurs</th>
  </tr>
  <tr>
    <td>background-color</td>
    <td style="background-color: yellow">
   acqua, green, navy, silver, black, gray, olive,
teal, blue, lime, purple, white, fuchsia, maroon,
red, yellow   
   </td>
  </tr>
  <tr>
    <td>font-family</td>
    <td style="background-color: yellow">serif , sans-serif , cursive ,
fantasy , monospace</td>
  </tr>
    
 <tr>
<td>text-align</td>
<td style="background-color: yellow"> center , left , right , justify</td>
</tr>
  
 <tr>
<td>border</td>
<td style="background-color: yellow">solid , dotted , dashed , double ,
inset , outset , groove , ridge , none , hidden</td>
</tr>
 <tr>
<td>text-decolaration</td>
<td style="background-color: yellow"> underline , overline </td>
</tr>
</table>


## Exemple de code 

```html
le code HTML :

<balise>
    contenu de la balise 
</balise>   

le code CSS :

    balise{
        background-color: blue ; 
        color: red ; 
        font-family: arial ; 
        font-style: normal ou italic ; 
        
    }

```




## Bibliographie

* [wikipedia](https://fr.wikipedia.org/wiki/Hypertext_Markup_Language) 
* [Openclassroom](https://openclassrooms.com/fr/)
* [image gratuite](https://pixabay.com/fr/photos/search/einstein/?min_width=16&min_height=16)
