# Espace vectoriel (e.v.)
corps $\mathbb K$ : un emsemble muni deux opérations + et .
### +
associative commutative neutre opposé
### . 
distributive unité
$$\mathbb R^\mathbb N  \,\,est \,\, bijective\,\,   \mathcal F = \{f: N \to R\}$$
## Produit fini et produit qcq.
## Combinaison linéaire d'un nombre fini et qcq. de vecteur
$$\sum_{k=1}^{n} \lambda_{k}x_{k}$$
# Sous-espace vectoriel (s.e.v.)
## Définition
$$0_E \in F$$
$$+ \,et \,.\, est \, stable  \Leftrightarrow combinaison\, stable$$
## Propriété
1. $E\, et\, 0_E$
2. $\cap \,\, de\,\,sev$ 
3. $\cup \,\, n'est \,\, pas,\,\, sauf \,\, si\,\, emsemble \,\,est \,\, inclu$
4. s.e.v +
## Engendré par A et génératrice
$$Vect(A)={x \in E, \exists n \in \mathbb N, \forall k \in [1,n], \exists \lambda_{k } \in \mathbb K, \exists a_{k}\in A,x=\sum_{k=1}^{n}\lambda_{k}a_{k}} $$
$Vect(\oslash)={0_{E}}$ et $Vect(F)=F$ et $Vect({x})=\mathbb Kx$
## Somme directe et supplémentaire
$$E_{1}+E_{2}\,\,est\,\,unique \to E_{1}\oplus E_{2}$$
Pour montrer que $E=E_{1}\oplus E_{2}$
+ il faut montrer que $E=E_{1}+E_{2}$ et $E_{1} \cap E_{2}=\{0\}$ 
+ la famille des bases est la base
+ il faut montrer que $dimE=dimE_{1}+dimE_{2}$ et $E_{1} \cap E_{2}=\{0\}$ 
## Base libre et liée
Libre : $\sum \lambda x=0$ $\to \lambda=0$
+ 有0 liee
+ sous-famille finie libre $\Longleftrightarrow$ famille libre
+ base $\Longleftrightarrow$ famille libre et génératrice 
# Ev de dimension finie
une base de cardinal fini
fini $\mathbb K^n$ et $C_{e.v.} \to R_{e.v.}$
infini $l'ensemble \,\,de\,\, fonction \,\, polynomiale$ et $\mathbb K[X]$
$dim \,\,de\,\, s.e.v \leq dim\,\, de\,\, e.v.$
## Théo de l'échange
$$p\leq n$$
$$(l_1,l_p,g_{i_{p+1}},g_{i_{n}})$$est une famille génératrice de E 
## Théo de la base incomplète
$$p\leq n$$
$$\exists l_{n-p},l_{n},\,\,on\,\, a  \,\,l_{1},l_{n}$$
une base de E
## Théo de Grassman
$$dim(F+G)=dimF+dimG-dim(F \cap G)$$
## Proposition
+ $E=F \oplus G \to dimE=dimF+dimG$
+ $dim(E_{1}\times E_{2})=dimE_{1}+dimE_{2}$
+ $F\subset G\,,\,dimF=dimG\to F=G$
# Applications linéaires
## Définition
$f: E \to E' (K-e.v.)$ qui vérifie $f(\lambda x+\mu y)=\lambda f(x)+\mu f(y)$ note $\mathcal L_{\mathbb K}(E,E')$
$f(E)=Im(f)$ et noyaux de f $f^{-1}(\{0_{E'}\})=Ker(f)$
itéré $f^0=id_{E}$ et $f^n=f \circ f^{n-1}$
homoMorphisme
+ E=E' endomorphisme $\mathcal L_{\mathbb K}(E)$
+ f bij isomorphisme
+ automorphisme $GL_{\mathbb K}(E)$
+ E' = $\mathbb K$ =E* de forme linéaire
## Propriété
+ $E\,\,et\,\,E'\,\,K-e.v. \to \mathcal L_{\mathbb K}(E,E')\,\,K-e.v.$
+ $F\,\,est\,\,s.e.v.\,\,de\,\,E\,\,et\,\,f \in \mathcal L_{\mathbb K}(E,E')\to f(F)\,\,une\,\,image\,\,est\,\,s.e.v.de\,\,E'$
+ $F'\,\,est\,\,s.e.v.\,\,de\,\,E'\,\,et\,\,f \in \mathcal L_{\mathbb K}(E,E') \to f^{-1}(F')\,\,est\,\,s.e.v.\,\,de\,\,E$
+ $f\,\,inj.\Longleftrightarrow Ker(f)=\{0_{E}\}$
+ $f\,\,surj. \Longleftrightarrow Im(f)=E'$
+ $f\,\,inj. \mathcal X\,\,famille\,\,libre\,\,de\,\,E\Longrightarrow f(x) libre$
+ $f\,\,surj\,\,\mathcal X\,\,géné .\Longrightarrow f(x)géné$
+ $f\,\,bj.\,\,\mathcal X\,\,base .\Longrightarrow f(x)base$
+ $\mathcal X géné \Longrightarrow Vect(f(x))=Im(f)$
+ compo de f,g liné est h liné
+ Ker de com grand, Im de com petit
+ endo gf=fg $\Longrightarrow$ g(im/ker(f)) petit
+ endo gf=fg=id_E $\Longrightarrow$  f bj
+ gf inj $\Longrightarrow$ f inj
+ gf inj, f suj $\Longrightarrow$ g inj
+ gf suj $\Longrightarrow$ g suj
+ gf suj, g inj $\Longrightarrow$ f suj
## Cas de la dimension finie
$$\dim\operatorname{Im}(f)\leq\dim E$$
$$\dim\operatorname{Im}(f)=\dim E\iff f\text{injective}$$
$$iso \,\,\iff\,\, même\,\, dim$$
$$\operatorname{rang}(f)\overset{\mathsf{Not}}{\operatorname*{=}}\dim(\operatorname{Im}(f))$$
$$rg(f)=\dim E'\iff f\text{surjective}$$
### Theo du rang
$$rg(f)=dimE-dimKer(f)$$
f endo est in-sur-bij
E E' dim fini donc dimL(E,E') =dimE* dimE'
## Projection
$$p_{F\parallel G}:x \to x_{F}$$
$p_{F\parallel G}+p_{G\parallel F}=id_E$
$p \circ p = p/0_{E}$
$Im(p)=F=\{x \in E,p(x)=x\}\,\, Ker(p)=G=Im(p)$
projecteur 
$p \circ p =p$
$E=Imp \oplus Kerp$
## Symétrie
$$s_{F\parallel G}:x_{F}+x_{G} \to x_{F}-x_{G}$$
$s \circ s = id_{E}$
s bj.
$s=p-p'=2p_{F\mid\mid G}-id_E$
## Restriction
$$\begin{cases}\mathscr{L}(E,E^{\prime})\to\mathscr{L}(F,E^{\prime})\\f\mapsto f_{|F}&\end{cases}$$
co-restriction
$$\begin{cases}\{f\in\mathscr{L}(E,E^{\prime}),\mathrm{~}f(E)\subset F^{\prime}\}\to\mathscr{L}(E,F^{\prime})\\f\mapsto f|^{F^{\prime}}&\end{cases}$$
prop
$$\mathrm{Ker}\left(f_{|_F}\right)=F\cap\mathrm{Ker}(f)$$
## Inclusion canonique
$$i_{F \subset E}=(id_E)_{|_F}:\begin{cases}F\to E\\x\mapsto x&\end{cases}$$
## Factorisation des applications linéaires
$$E=Kerf\oplus F$$
$$\left.f\right|_F^{\operatorname{Im}(f)}\text{est un isomorphisme entre }F\text{et }\operatorname{Im}(f)$$
## Systèmes linéaires
$$\mathrm{Sol}(\mathscr{S})=\{x\in E,~u(x)=e^{\prime}\}$$
### condition de compatibilité
$$e' \in Im(u)$$
système homogène 
$$Sol(f)=x_{0}+Ker(u)$$
Principe de superposition des solutions
$A.X=B$ a une matrice augmentée $[A|B]$ rg ne change pas
de Cramer $X=A^{-1}.B$ lorsque A inversible
La matrice A est inversible si et seulement si sa forme échelonnée réduite est la matrice identité Ip

## Interpolation de Lagrange_interpolation polynomiale
E_n qui contient Deg(fp)=< n

# Matrice
$$f(x)=\sum_{j=1}^nx_{j}f(e_{j})=\sum_{j=1}^nx_{j}\sum_{i=1}^na_{i,j}e_{i}'=\sum_{j=1}^n(\sum_{j=1}^nx_{j}a_{i,j})e_{i}'$$
$M_{n,p}(\mathbb K)=[a_{i,j}]$ à n ligne et p colonne
## Pivot de Gauss
+ changer ligne
+ combinaison
échelonné (réduit)
vecteur directeur/support
imcompatible 无解
## Oppération
### Addition 
### Multiplication 
### Produit
$c_{i,j}=\sum_{k=1}^p a_{i,k}b_{k,j}$
$A.B\neq B.A$    
commutent $(A+B)^k=\sum_{\ell=0}^k\binom k\ell.A^\ell.B^{k-\ell}$
$A.B.C=A.B.C$
$A^k=A^{k-1}.A$ 
### Transposée
T est application linéaire
Involutive ${}^t({}^tA)=A$
Contravariante ${}^t(A.B)={}^tB.{}^tA$
$S_{p}(\mathbb K)=\{{}^tM=M\}$
$A_{p}(\mathbb K)=\{{}^tM=-M\}$
$S\oplus A=M$
Dim
### Matrice identité d'ordre p
$I_{n}.A=A.I_{p}=A$
$0.A=A.0=0$
### Trace
$trace (A)=\sum_{k=1}^pa_{k,k}$ forme linéaire 
$trace(^tA)=trace(A)$
$trace(A.B)=trace(B.A)$
### Inverse
inversible $A.A^{-1}=A^{-1}.A=I_{p}$
$GL_{p}(\mathbb K)$
$(A^{-1})^{-1}=A$
$(A.B)^{-1}=B^{-1}.A^{-1}$
$A^{-k}=(A^k)^{-1}$
$(^tA)^{-1}=^t(A^{-1})$
$$
A^{-1}=\frac{1}{ad-bc}\begin{bmatrix}
d &-b \\
-c& a
\end{bmatrix}
$$
#### Transvection
$T_{k,\ell}(\lambda)=I_p+\lambda.E_{k,\ell}$ et $(T_{k,\ell}(\lambda))^{-1}=T_{k,\ell}(-\lambda)$
左行右列
#### Dilatation
$D_{k}(\lambda)=I_{p}+(\lambda-1)E_{k,k}$ et $D_{k}(\lambda)^{-1}=D_{k}\left( \frac{1}{\lambda} \right)$
#### Permutation
$P_{\sigma}=[\delta_{i,\sigma(j)}]_{(i,j)\in[1,p]^2}$ et $(P_{\sigma})^{-1}=P_{\sigma^{-1}}$
Matrice de transvection ; Matrice de dilatation ; Matrice de permutation sont inversibles
Produit des matrices élémentaires est inversible
### Théo du pivot généralisé de Gauss
$R_1\cdot\cdots\cdot R_q\cdot A\cdot S_1\cdot\cdots\cdot S_s=J_{n,p,r}$
$R_1\cdot\cdots\cdot R_q\cdot A=I_{p}=A\cdot S_1\cdot\cdots\cdot S_s$ inversible
Lorsque l’on calcule un rang : on peut travailler à la fois sur les lignes et les colonnes. 
Lorsque l’on résout un système d’équations linéaires, on ne travaille que sur les lignes. 
Lorsque l’on calcule un noyau, on ne travaille que sur les lignes . 
Lorsque l’on calcule une image, on ne travaille que sur les colonnes.
### Matrice-blocs

## Base canonique
$E_{k,l}=[\delta_{i,k} \delta_{j,l}]$ Matrice dans une base
$$\operatorname{Mat}_{\mathscr E}(x)=\begin{bmatrix}x_1 \\\vdots\\ x_p\end{bmatrix}$$
$$\operatorname{Mat}_{\mathscr{E},\mathscr{E}^{\prime}}(f)=\begin{bmatrix}a_{1,1}&\cdots&a_{1,p}\\\vdots&\ddots&\vdots\\a_{n,1}&\cdots&a_{n,p}\end{bmatrix}\in M_{n,p}(\mathbb{K})$$
Isomorphe de f -->Mat (f) $Mat_{\mathcal E'}(f(x))=Mat_{\mathcal E,\mathcal E'}(f).Mat_{\mathcal E}(x)$
composé $\underbrace{\mathrm{Mat}_{\mathscr{E},\mathscr{E}^{\prime\prime}}(\boldsymbol{g}\circ\boldsymbol{f})}_{\in\mathrm{M}_{\boldsymbol{q},\boldsymbol{\rho}}(\mathbb{K})}=\underbrace{\mathrm{Mat}_{\mathcal{E}^{\prime},\mathcal{E}^{\prime\prime}}(\boldsymbol{g})}_{\in\mathrm{M}_{\boldsymbol{q},\boldsymbol{n}}(\mathbb{K})}\bullet\underbrace{\mathrm{Mat}_{\mathcal{E},\mathcal{E}^{\prime}}(\boldsymbol{f})}_{\in\mathrm{M}_{\boldsymbol{n},\boldsymbol{\rho}}(\mathbb{K})}$
Inversible $Mat_{E}(f^{-1})=(Mat_{E}(f))^{-1}$
### Matrice de passage 
$P_{\mathscr E}^{\mathscr B}=Mat_{\mathscr B}(\mathscr E)=Mat_{\mathscr B,\mathscr E}(id_{E})$
+ $(P_{\mathscr B}^{\mathscr E})^{-1}=P_{\mathscr E}^{\mathscr B}$
+ $P_{\mathscr E}^{\mathscr C}=P_{\mathscr E}^{\mathscr B}.P_{\mathscr B}^{\mathscr C}$
+ $Mat_{\mathscr E}(x)=P_{\mathscr E}^{\mathscr B}. Mat_{\mathscr B}(x)$
+ $\operatorname{Mat}_{\mathscr{B},\mathscr{B}^{\prime}}(f)=\left(P_{\mathscr{E}^{\prime}}^{\mathscr{B}^{\prime}}\right)^{-1}.\operatorname{Mat}_{\mathscr{B},\mathscr{B}^{\prime}}(f).P_{\mathscr{B}}^{\mathscr{B}}$
### Noyau et image
$Ker (A/f)=\{X \in M_{p,1}(\mathbb K),\,\,A.X=0_{n,1}\}$
$Im (A/f)=\{A.X,\,\,X \in M_{p,1}(\mathbb K)\}$
+  $p=rangA+dimKerA$
+ $inversible\Longleftrightarrow  KerA={0_{p,1}}\Longleftrightarrow rgA=p \Longleftrightarrow C_{1},\dots,C_{p}\,\,est\,\,une\,\,base\,\,de\,\,M_{p,1}(\mathbb K)$
+  $GLp, n rgA=rgX$
+  $rg(^tA)=rgA$
### Relations d’équivalence
réflexive $xRx$
symétrique $xRy \to yRx$
transitive $xRy,yRz \to xRz$
+ m^ dim
+ en bij
+ m^ reste dans la division euclidienne
Si $N=P.M.Q$, $M\approx N$ équivalence
Si $N=P^{-1}.M.P$ $M\sim N$ similitude et carré
+ équivalence m^ al.
+ semblable m^ endo. AB et BA
Det, rg, trace
$rangA=r \leftrightarrow \text{A est équivalent à} \,J_{n,p,r}$
$\begin{aligned}&\texttt{Deux matrices de M}_{n,p}(\mathbb{K})\text{ sont équivalentes si, et seulement si, elles} \\&\text{ont même rang.}\end{aligned}$

# Déterminant
Surface
## Permutation 
Bijective, non vide
$card\mathbb\sigma_{p}=P!$
Composé et inverse $\to$ permutation
### Composition
+ Élément neutre $id_{E}$ 
+ Élémant inverse
+ Associative 
+ Stable 
[[#Groupe symétrique]]
### Transposition
$\tau_{i,j}(i)=j$
$\tau^{2}=id$ et $\tau^{-1}=\tau$
### Signature
$\varepsilon(\sigma)=\Pi_{1\leq i<j\leq p} \frac{\sigma(j)-\sigma(i)}{j-i}$
Parité de transposition gagne un signe positif
Prop
$\sigma=\tau_{1}\circ\tau_{2}$
$\varepsilon(\sigma \circ\sigma')=\varepsilon(\sigma)\varepsilon(\sigma')$

## Formes p-linéaires sur un espace vectoriel
$$
\phi:\begin{cases}E^p\to\mathbb{K}\\(x_1,\ldots,x_p)\mapsto\phi(x_1,\ldots,x_p)&\end{cases}
$$
### Symétrique
Indice permutation
### Antisymétrique 
multiplier la signature
### Alternée 
existe au moins deux coordonées égale donc $\phi =0$
Liée, antisymétrique, $\phi =0$
$DimA_n(E,K)=1$
## Déterminant
forme n-linéaire, antisymétrique (alternée)
+  $\sum_{\sigma \in(\S_{n})}\varepsilon(\sigma)\prod_{j=1}^n a_{\sigma(j),j}$
+ dimension 1, de base (D), f = f (e 1, . . . , en).D
+ $\det_{B}=\det_{B}E.\det_{E}$
+ $\det\neq 0$ inversible et $\det(A^{-1})=\frac{1}{\det(A)}$
+ $\det(\lambda A)=\lambda^n\det A$ 
+ $\det(A.B)=\det A\det B$
+ $\det (^tA)=\det A$


- Liée 0, 00000 réduit, pivot et comatrice
$A^tcom(A)=^tcom(A)A=\det(A)I_{n}$
- Dev






# Qch d'important
## Calcul
AM=MA, solution
Nilpotente, binôme de Newton
Récurrence
## Inverse
Inversible -- detA $\neq$ 0
Pivot
Équation isolant In et A
AB=BA=In dimention finie
## Rang
Colonne -- Ker
$e_{1},e_{2},e_{3}$
Changement de base
## Triangulaire
Somme, produit -- Tri
Tri + dia non nul
## Trace
$^{t}(\alpha A+B)=\alpha ^{t}A+^{t}B)$
$^{t}(AB)=^{t}B^{t}A$
$Trace (\alpha A+B)=\alpha Trace(A)+Trace(B)$
$tr(AB)=tr(BA)$
$tr(^{t}A)=tr(A)$
$dimA_{n}=\frac{n(n-1)}{2}$
# Espaces euclidiens
## Produit scalaire
$\phi : E*E \to \mathbb R$ Bilinéaire
$\phi(x,y)=\phi(y,x)$ symétrique
$\phi(x,x)\geq 0$ positive
$\phi(x,x)=0 \to x=0_{E}$ définie
+ E E.v.préhibertien, E finie E.e.
+ Sym - liné - posi et défi
+ $\left \langle x,y \right \rangle$
+ $\mid \phi(x,y)\mid^2\leq \phi(x,x)\phi(y,y)$ liée Inégalité de Cauchy-Schwarz
+ $\phi(x,y)=0$ orthogonaux
## Norme
$\mid\mid\,\,\mid\mid: E \to R_{+}$ positivité
$\begin{aligned}&\quad\forall x\in E,\|x\|=0\iff x=0_E\text{ (caractère défini).}\\&\quad\forall x\in E,\forall\lambda\in\mathbb{R},\|\lambda.x\|=|\lambda|\|x\|\text{ (homogénéité).}\\&\quad\forall(x,y)\in E^2,\|x+y\|\leq\|x\|+\|y\|\text{ (inégalité triangulaire).}\end{aligned}$
+ espace vectoriel normé
+ norme euclidienne : E E.p.r, muni de $\phi$ donc $x \to \sqrt{ \phi(x,x) }$
+ l’identité de la médiane ou du parallélogramme $\forall(x,y)\in E^2,~\|x+y\|^2+\|x-y\|^2=2\left(\|x\|^2+\|y\|^2\right)$
+ unitaire e.p.r
$(x,y)\mathrm{~orthogonaux~}\Longleftrightarrow\|x+y\|^2=\|x\|^2+\|y\|^2$
orthonormale libre + finie = base $x=\sum\left \langle x,e_{i} \right \rangle.e_{i}$, $\left \langle x,y \right \rangle=\sum\left \langle x,e_{i} \right \rangle\left \langle y,e_{i} \right \rangle=\sum\left \langle x_{i},y_{i} \right \rangle$, $\mid\mid x\mid\mid=\sqrt{ \sum x^2_{i} }$
Banach
### Procédé d’orthonormalisation de Schmidt
E.p.r base peut trouver unique famille orthonormale, et $\left \langle u_{k},e_{k} \right \rangle>0$
E.e une base orthonormée
E.p.r base dénombrable, donc ortho
8
Projection orthogonale $\sum_{i=1}^{n-1} \langle u_{n+1},e_{i}\rangle e_{i}$
### Orthogonal
$A^{\perp.}=\{x\in E,\mathrm{~}\forall a\in A,\mathrm{~}\langle a,x\rangle=0\}$, avec E e.p.r et $A\subset E$
+ $A^{\perp.}$ s.e.v. E
+ $A=\emptyset \,\,A^{\perp.}=E$
+ $A\cap A^{\perp.}=0_{E}$
+ $A \subset B \to A^{\perp.} \supset B^{\perp.}$
+ $A \subset (A^{\perp.})^{\perp.}$
+ $A^{\perp.}=(VectA)^{\perp.}$
+ $(F+G)^{\perp.}=F^{\perp.}\cap G^{\perp.}$
Fini
+ $E=F\oplus F^{\perp.}$
+ $F = (F^{\perp.})^{\perp.}$
+ un supplémentaire mais le supplémentaire orthogonal
+ Projection orthogonale $p_{u}(x)= \frac{\left\langle x,u \right\rangle}{\mid\mid u\mid\mid^2}.u$
### Hyperplan
$\exists\varphi\in \mathcal L(E,\mathbb K)\setminus\{0_{L(E,\mathbb K)}\},~H=\mathrm{Ker}(\varphi)$
Équation de l’hyperplan $(H)~\varphi(x)=0$
+  $H={n}^{\perp.}=(a_{i})$
+ $p_{H}=x-p_{n}$
+ $p_{F}(x)=\sum_{k=1}^n\langle e_{k},x\rangle .e_{k}$
+ $E_{i}\perp E_{j}$ 
## Sorte
![[Sorte de l'espace.canvas]]
