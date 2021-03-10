# **Apunts_UF2_2**

## **ENTORNS DE DESENVOLUPAMENT**

### **OPTIMITZACIÓ**

### **Hediondez del codi**

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
