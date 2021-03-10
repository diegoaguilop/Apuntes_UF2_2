# **Apunts_UF2_2**

## **ENTORNS DE DESENVOLUPAMENT**

### **OPTIMITZACIÓ**

### **Hediondez del codi**

L'Hediondez del codi o code smell és qualsevol símptoma en el codi font d'un programa que possiblement indica un problema més profund.Indiquen deficiències en el disseny del programari que poden alentir el desenvolupament o augmenten el risc d'errors.És un motiu important per a realitzar refactorització.

* Exemples:
  * **Codi duplicat:** Hi ha codi idèntic o molt similar en més d'una ubicació.

  * **Molts paràmetres:** Una llarga llista de paràmetres d'un procediment o funció empitjora la llegibilitat i la qualitat de el codi.

  * **Enveja de característiques:** Una classe que fa servir excessivament mètodes d'una altra classe.

  * **Classe mandrosa:** Una classe que fa molt poc.

  * **Identificadors excessivament curts i incoherents:** El nom d'una variable ha de reflectir la seva funció, llevat que sigui obvi.

  * **Classe gran:** Una classe que ha crescut fins a ser massa gran.

  * **Mètode gran:** 1 mètode , funció o procediment que ha crescut fins a ser massa gran.

----------------------

### **Anàlisi de codi**

* **Anàlisi dinàmic:**
  * Utilitzen els unit tests.

* **Anàlisi estàtic:**
  * Utilitzen els analitzadors estàtics (**linters**):
    * **lint** : C
    * **sonar** : Java
    * **JSLint** , **ESLint** : Javascript

  * Utilitzen llocs web que ofereixen inspecció de codi:
    * **Scrutinizer**
    * **SonarQube**
----------------------

### **Refactorització**

* És el procés de reestructurar un codi font, alterant la seva estructura interna sense canviar el seu comportament extern.

* Tècniques:
  * Renom de variables
  * Passar codi duplicat a funcions
  * Eliminació de codi inabastable
  * Eliminació de codi redundant
  * Eliminació de codi mort
----------------------

### **DOCUMENTACIÓ**

### **Tipus de documentació**

* **Documentació de codi**
* **Documentació tècnica**
* **Documentació d'usuari**
----------------------

### **Formats de documentació**

* **Markdown** (p. Ex. Gitbook)
* **HTML** (p. Ex. Javadoc)
* **reStructuredText** (p. ex. Readthedocs)
* **asciiDoc**
----------------------

### **CONTROL DE VERSIONS**

### **Sistemes més coneguts**

* **CVS**
* **Subversion**
* **Mercurial**
* **Git**

### **GIT**

* **Característiques:**
  * Eficient
  * Modern
  * Distribuït

* **Conceptes:**
  * **Repository** (local & remote)
  * **Commit**
  * **Branch**
    * **Checkout**
    * **Merge** (fast-forward, 3-way)

* **Àrees:**

![](git-areas1.png)

![](git-areas2.png)

* **Branques:**

![](git-branches.png)


* **Ordres:**
~~~
# Configuración
  config 

# Repositorios
  clone, remote add, remote rm

# Básicos
  init, status, log, add, rm, commit, push, pull

# Ramas (branches)
  branch, branch -d, merge, checkout, stash

# Otros
  diff, tag, submodule
~~~

* **Llocs que suporten GIT:**
 * **GitHub**
 * **Bitbucket**
 * **GitLab**
 * **Coding -en xinès-**
----------------------
