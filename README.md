<h1 align="center">Welcome to readme scraping 👋</h1>
<p align="center">
  <a href="https://twitter.com/LaurentJouron">
    <img alt="Twitter: LaurentJouron"
      src="https://img.shields.io/twitter/follow/LaurentJouron.svg?style=social" target="_blank" />
  </a>   
  <a href="https://github.com/LaurentJouron">
    <img alt="GitHub followers" 
      src="https://img.shields.io/github/followers/LaurentJouron?style=social" />
  </a>
</p>
<p align="center">
    <img align="left"
      width="60px" 
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSX4PiKOshpQfsfBToRmImIP_XLnyDnKDOL5A&usqp=CAU" />
</p>

### ``--- Explanation in English ---``

___________

This was done as part of a training course on :

___

You are a marketing analyst at Books Online, a major online bookstore specializing in used books. As part of your job, 
you try to manually track the prices of used books on your competitors' websites, but that’s too much work, and you can’t
cope with it: there are too many books and too many online bookstores ! You and your team decided to automate this
laborious task via a program (a scraper) developed in Python, able to extract price information
from other online libraries.

___________

# Books Online

*In order to better manage the company in which I work, I created a scraping application on the website
Book-toScrape.com. Scraping is a method of extracting data to analyze information.*

https://books.toscrape.com/

___________

<h1 align="center">Purpose of the application</h1>

___

<p align="center">
    <img align="right"
      width="350px" 
      src="https://www.e-bdd.com/images/scraping-web.webp" />
</p>

* Initially this software will take:
  * the names of the categories
  * category links.
 
* Then according to the links of the Categories, it will load :
  * the titles of the books
  * the links of the books
  * the covers of books

<p align="center">
    <img align="right"
      width="350px"
      src="https://www.okvoyage.com/wp-content/uploads/2021/01/bibliotheque-nationale-finlande-1024x683.jpeg" />
</p>
      
* Finally, he will retrieve the information from the books :

  * UPC (universal_product_code)
  * product_type
  * price_excl_tax
  * price_incl_tax
  * tax
  * available_in_stock
  * number_of_review
  * synopsis
___________

<h1 align="center">Language</h1>

___

<p align="center">
    <img align="center"
      width="500px"
      src="https://static.lpnt.fr/images/2017/11/06/11154015lpw-11154254-article-jpg_4741099_660x281.jpg" />
</p>

<p align="center">The entire application was developed in Python .</p>
    
<table>
  <tr>
    <td align="center">
      <a href=https://www.python.org/">
        <img width="200px"
          src="https://www.python.org/static/img/python-logo.png" /><br />
        <sub><b>Download Python</b></sub></a><br />
      <a href=https://www.python.org/" title="Download Python" ></a> 
    </td>
  </tr>
</table>
 
___________

<h1 align="center">IDE</h1>

___

The IDE used for programming is Pycharm. 
    
<table>
  <tr>
    <td align="center">
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows">
        <img width="130px"
          src="https://www.qbssoftware.fr/image/cache/catalog/Editeurs/Jetbrains/jetbrains-pycharm-164-1600x1600.jpg" /><br />
        <sub><b>Download Pycharm</b></sub></a><br />
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows" title="Download Pycharm" ></a> 
    </td>
  </tr>
</table>

It has been tested with :

<table>
  <tr>
    <td align="center">
      <a href="https://www.sublimetext.com/3">
        <img width="110px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6Mg79M0jZejQAa6OE5Hh1td-RE6Cs7pQ6Og&usqp=CAU" /><br />
        <sub><b>Sublime text 3</b></sub></a><br />
      <a href="https://www.sublimetext.com/3" title="Sublime text 3" ></a>
    </td>
    <td align="center">
      <a href="https://visualstudio.microsoft.com/fr/">
        <img width="130px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-H3CcAG7w2nXSnlqldVWR-ER4mvFfLgqYxA&usqp=CAU" /><br />
        <sub><b>Visuable Studio Code</b></sub></a><br />
      <a href="https://visualstudio.microsoft.com/fr/" title="Visuable Studio Code" ></a>
    </td>
    <td align="center">
      <a href="https://jupyter.org/">
        <img width="150px"
          src="https://jupyter.org/assets/nav_logo.svg" /><br />
        <sub><b>Jupyter Notebook</b></sub></a><br />
      <a href="https://jupyter.org/" title="Jupyter Notebook" ></a> 
    </td>
  </tr>
</table>

___________

<h1 align="center">Library</h1>

___

We used 3 different libraries for this project, here are the explanatory documents:
  
<table>
  <tr>
    <td align="center">
      <a href="https://docs.python-requests.org/en/latest">
        <img width="130px"
          src="https://docs.python-requests.org/en/latest/_static/requests-sidebar.png" /><br />
        <sub><b>Requets</b></sub></a><br />
      <a href="https://docs.python-requests.org/en/latest" title="Documentation Requests" ></a>
    </td>
    <td align="center">
      <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/">
        <img width="130px"
          src="https://www.crummy.com/software/BeautifulSoup/bs4/doc/_images/6.1.jpg" /><br />
        <sub><b>BeautifulSoup</b></sub></a><br />
      <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/" title="Documentation BeautifulSoup" ></a>
    </td>
    <td align="center">
      <a href="https://docs.python.org/fr/3/library/csv.html">
        <img width="150px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTeFQCFFmRX7dsxcyLmKNYn9Umgdg71FDMsZQ&usqp=CAU" /><br />
        <sub><b>csv</b></sub></a><br />
      <a href="https://docs.python.org/fr/3/library/csv.html" title="Documentation csv" ></a> 
    </td>
    <td align="center">
      <a href="https://docs.python.org/3/library/os.html">
        <img width="150px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGeVC6EubMa9PBsn1aoXsbCmGEVENRpb9wlg&usqp=CAU" /><br />
        <sub><b>os</b></sub></a><br />
      <a href="https://docs.python.org/3/library/os.html" title="Documentation csv" ></a> 
    </td>
  </tr>
</table>

___________

<h1 align="center">Software installation</h1>

___
<p align="left">For the terminal I used GIT.

<table>
  <tr>
    <td align="center">
      <a href=https://git-scm.com/downloads">
        <img width="130px"
          src="https://git-scm.com/images/logo@2x.png" /><br />
        <sub><b>Download GIT</b></sub></a><br />
      <a href=https://git-scm.com/downloads" title="Download GIT" ></a> 
    </td>
  </tr>
</table>


<p align="left">Control Mac et Linux .

<table>
  <tr>
    <td align="center">
      <a href=https://www.apple.com/fr/store">
        <img width="130px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR4Sp8Lrrw6oLYyresDDFX4l_CAd_fsTU_XpWNUqtFeu3HYAZ6TaeVJGI22V6pDIugmfD8&usqp=CAU" /><br />
        <sub><b>Apple</b></sub></a><br />
      <a href=https://www.apple.com/fr/store" title="Apple" ></a> 
    </td>
    <td align="center">
      <a href=https://www.ubuntu-fr.org/">
        <img width="130px"
          src="https://www.ubuntu-fr.org/img/logo.svg" /><br />
        <sub><b>Linux</b></sub></a><br />
      <a href=https://www.ubuntu-fr.org/" title="Linux" ></a> 
    </td>
  </tr>
</table>


* To start you must clone the project with the following url :
  * ``git clone https://github.com/LaurentJouron/books-toscrape.com.git``
  

* There is no virtual environment, so you must create it with the command :
  * ``python -m venv env``


* Enable this environment, with the command : 
  * ``source/env/bin/activate``


* After installing the environment, you must set the libraries on which the software was developed, use the following command : 
  * ``pip install -r requirements.txt``


* To test if all packages have been configured correctly : 
  * ``pip freeze``


* Then all that remains is to run the script so that the software starts with the command : 
  * ``pip main.py``


* Click Run to activate the program :
  * ``Run``

___________

As the process progresses, we note the writing of .csv files that allow the analysis of the information of the books .

<p align="center">
    <img align="center" 
      width="350px" 
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTRCQnMkK3eTUga21tSq4dsh6xBfffxX5YWVg&usqp=CAU" />
</p>

___________

<h1 align="center">Author and collaborators</h1>

___

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/LaurentJouron">
        <img width="100px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlW-w7O7g3hQTw8qcIAy3LCRhiHg5tUPfvVg&usqp=CAU" /><br />
        <sub><b>Laurent Jouron</b></sub></a><br />
      <a href="https://openclassrooms.com/fr/" title="student">🈸</a>
      <a href="https://github.com/LaurentJouron/Books-online" title="Application Coder">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/thierhost">
        <img width="100px"
          src="https://avatars.githubusercontent.com/u/7854284?s=100&v=4" /><br />
        <sub><b>Thierno Thiam</b></sub></a><br />
      <a href="https://github.com/thierhost" title="Mentor to Laurent">👨‍🏫</a> 
      <a href="https://www.python.org/dev/peps/pep-0008/" title="Doc PEP 8">📄</a>
    </td>
  </tr>
</table>

___________

#####################################################################################

___________

<h1 align="center">Bienvenue sur mon profil GitHub😉</h1>
<p align="center">
  <a href="https://twitter.com/LaurentJouron">
    <img alt="Twitter: LaurentJouron" 
      src="https://img.shields.io/twitter/follow/LaurentJouron.svg?style=social" target="_blank" />
  </a>
  <a href="https://github.com/LaurentJouron">
    <img alt="GitHub followers" 
      src="https://img.shields.io/github/followers/LaurentJouron?style=social" />
  </a>
</p>

<p align="center">
    <img align="left"
      width="50px" 
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToscdusMNjQbffwasgiLuCsbCNZisJRE95Fg&usqp=CAU" />
</p>

### ``--- Explication en français ---``

Après 28 ans passé dans le domaine de la coiffure, je me réoriente dans un univers qui me passionne depuis toujours, l'informatique et plus précisément dans le développement d'application.
___________

<h2 align="center">Expressions-Parfumées et OpenClassrooms</h2>



*Pour réussir la mission que je me suis fixée, je suis en altérnance dans une entreprise de parfumerie à Grasse : <a href="https://www.epparfums.com/" target="_blank">Expressions parfumées</a> et je suis les cours à distance sur la plateforme : <a href="https://openclassrooms.com/fr/" target="_blank">OpenClassrooms</a>.*
___________

<h2 align="center">Langage travaillé chez Expressions-Parfumées</h2>

<table>
  <tr>
    <td align="center">
      <a href=https://pcsoft.fr/windev/index.html">
        <img width="120px"
          src="https://pcsoft.fr/img/logo-pcsoft.svg" /><br />
        <sub><b>Windev</b></sub></a><br />
      <a href=https://pcsoft.fr/windev/index.html" title="Windev" ></a> 
    </td>
        <td align="center">
      <a href=https://sql.sh">
        <img width="120px"
          src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Sql_database_shortcut_icon.png" /><br />
        <sub><b>SQL</b></sub></a><br />
      <a href=https://sql.sh/" title="SQL" ></a> 
    </td>
  </tr>
</table>

__________

<h2 align="center">Langage travaillé chez OpenClassrooms</h2>

<table>
  <tr>
    <td align="center">
      <a href=https://www.python.org/">
        <img width="120px"
          src="https://www.python.org/static/img/python-logo.png" /><br />
        <sub><b>Téléchargez Python</b></sub></a><br />
      <a href=https://www.python.org/" title="Téléchargez Python" ></a> 
    </td>
  </tr>
</table>

__________

<h2 align="center">Formation développeur d'application Python chez OpenClassrooms</h2>


La formation se décompose en 13 projets, qui contient des modules avec certificats à la clef.
Voici ceux qui sont validés.
___

1 - Prenez en main votre formation :
  * Comprendre le Web
  * Mettez en place un système de veille informationnelle
  * Développez vos soft skills
  * Apprendre à apprendre
  * Gérez votre temps efficacement
___

2 - Utilisez les bases de Python pour l'analyse de marché :
  * Apprenez les bases du langage Python
  * Initiez-vous à Pyhon pour l'analyse de données
  * Apprenez à utiliser la ligne de commande dans un terminal
  * Metter en place votre environnement Python
  * Prenez la parole en public
  * Gérez du code avec Git et GitHub

___

3 - Designez une application Python adaptée aux besoins d'un client
  * Initiez-vous à la gestion de projet agile


___

Par ailleurs, je me suis investit dans d'autre module pour mieux comprendre les besoins de l'informatique.
Voici ceux qui sont validés.

  * Découvrez le fonctionnement des algorithmes

___

<h2 align="center">Formation divers</h2>

Avant de me reconvertir, j'ai suivi une formation professionnelle sur Excel et la programmation en VBA

<table>
  <tr>
    <td align="center">
      <a href=https://www.microsoft.com/fr-fr/microsoft-365/excel">
        <img width="120px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwJF7oQXulwnHM0ZMMHEfz6ZpP-nffAyNpWDK2UkPnwSctlw-9CK8UEGT4ZVDy8tEQ4Lc&usqp=CAU" /><br />
        <sub><b>Excel</b></sub></a><br />
      <a href=https://www.microsoft.com/fr-fr/microsoft-365/excel" title="Excel" ></a> 
    </td>
  </tr>
</table>

___


<h2 align="center">Formation Udemy</h2>

Afin de renforcer le besoin, pour l'entreprise comme pour mes cours, j'ai suivi quelques formations sur le site <a href="https://www.udemy.com/" target="_blank">Udemy</a>.
<table>
  <tr>
    <td align="center">
      <a href=https://www.udemy.com/">
        <img width="100px"
          src="https://www.udemy.com/staticx/udemy/images/v7/logo-udemy.svg" /><br />
        <sub><b>Udemy</b></sub></a><br />
      <a href=https://www.udemy.com/" title="Udemy" ></a> 
    </td>
  </tr>
</table>

  * Formation Git et Github de débutant à confirmé (Arnaud Mercier)
  * La formation Complète Python (Thibault Houdon)
  * Python par la pratique: 101 Exercices corrigéés (Thibault Houdon)
  * Devenez un expert du web scraping - la formation - (Sebastien Daviot)
  * La formation Complète PyCharm (Tibault Houdon)
  * SQL Server pour les (grands) débutant, 8 heures de pratique (Olivier Thuillier)
  * GNU/Linux de débutant à confirlé en quelques heures (Jordan Assouline)
  * SQL pour la Data Science de A à Z (analyse de data réelles) (Rod)
  * Développeur Python Formation Complète 2021 (Jonathan Roux)
  * Découverte de Linux et Shell [Ubuntu / Bash / 2021 / Intro] (Sébastien C)
  * Developpeur d'Application Mobiles | Formation Complète 2021 (Jonathan Roux)
  * PHP et MySQL : la formation ULTIME (Louis Nicolas Leuillet)
  * SQL Server: Le cours complet de 27 heures (13 cours en 1) (Olivier Thuillier)
  * Les bases indispensables de la programmation: Algorithmique (Matthieu Gaston )
  * 51 exercices d'algorithmique (avec Milo) (Matthieu Gastion)
  * Blender 2.8 la formation du débutant à l'avancé (Julien Deville)
  * HTML5 et CSS3 : le formation ULTIME (Louis Nicolas Leuillet)

___________

<h1 align="center">EDI</h1>


<p align="left">L'EDI que j'utilise pour la programmation est Pycharm .

<table>
  <tr>
    <td align="center">
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows">
        <img width="130px"
          src="https://www.qbssoftware.fr/image/cache/catalog/Editeurs/Jetbrains/jetbrains-pycharm-164-1600x1600.jpg" /><br />
        <sub><b>Téléchargez Pycharm</b></sub></a><br />
      <a href=https://www.jetbrains.com/fr-fr/pycharm/download/#section=windows" title="Téléchargez Pycharm" ></a> 
    </td>
  </tr>
</table>

Toutefois je test avec :

<table>
  <tr>
    <td align="center">
      <a href="https://www.sublimetext.com/3">
        <img width="110px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6Mg79M0jZejQAa6OE5Hh1td-RE6Cs7pQ6Og&usqp=CAU" /><br />
        <sub><b>Sublime text 3</b></sub></a><br />
      <a href="https://www.sublimetext.com/3" title="Sublime text 3" ></a>
    </td>
    <td align="center">
      <a href="https://visualstudio.microsoft.com/fr/">
        <img width="130px"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-H3CcAG7w2nXSnlqldVWR-ER4mvFfLgqYxA&usqp=CAU" /><br />
        <sub><b>Visuable Studio Code</b></sub></a><br />
      <a href="https://visualstudio.microsoft.com/fr/" title="Visuable Studio Code" ></a>
    </td>
    <td align="center">
      <a href="https://jupyter.org/">
        <img width="150px"
          src="https://jupyter.org/assets/nav_logo.svg" /><br />
        <sub><b>Jupyter Notebook</b></sub></a><br />
      <a href="https://jupyter.org/" title="Jupyter Notebook" ></a> 
    </td>
  </tr>
</table>

___________


<p align="left">Pour le terminal j'utilise GIT .

<table>
  <tr>
    <td align="center">
      <a href=https://git-scm.com/downloads">
        <img width="130px"
          src="https://git-scm.com/images/logo@2x.png" /><br />
        <sub><b>Téléchargez GIT</b></sub></a><br />
      <a href=https://git-scm.com/downloads" title="Téléchargez GIT" ></a> 
    </td>
  </tr>
</table>

___

<h1 align="center">Auteur et collaborateurs</h1>

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/LaurentJouron">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlW-w7O7g3hQTw8qcIAy3LCRhiHg5tUPfvVg&usqp=CAU"
          width="100px;"/><br />
        <sub><b>Laurent Jouron</b></sub></a><br />
      <a href="https://openclassrooms.com/fr/" title="Étudiant">🈸</a>
      <a href="https://github.com/LaurentJouron" title="Codeur d'application">💻</a>
    </td>
    <td align="center">
      <a href="https://github.com/thierhost">
        <img src="https://avatars.githubusercontent.com/u/7854284?s=100&v=4"
          width="100px;"/><br />
        <sub><b>Thierno Thiam</b></sub></a><br />
      <a href="https://github.com/thierhost" title="Mentor de Laurent">👨‍🏫</a> 
    </td>
  </tr>
</table>
