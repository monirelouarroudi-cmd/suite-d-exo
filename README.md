# ➕ Exercices supplémentaires — Entraînement TG-E-02

**Terminale · Spécialité Maths**

> Deux nouveaux exercices pour chacun des trois types du devoir blanc : **vecteurs dans le cube** (exercice 1), **formule de Leibniz** (exercice 3) et **repère dans un pavé** (exercice 4). Chaque exercice vaut **3 points** et est suivi de son corrigé détaillé.

---

## 📑 Sommaire

**Type exercice 1 — Vecteurs dans le cube**
- [Exercice 1-A — Centre de gravité et alignement](#exercice-1-a--centre-de-gravité-et-alignement-3-points)
- [Exercice 1-B — Un parallélogramme dans le cube](#exercice-1-b--un-parallélogramme-dans-le-cube-3-points)

**Type exercice 3 — Formule de Leibniz**
- [Exercice 3-A — Formule de Leibniz, niveau facile](#exercice-3-a--formule-de-leibniz-niveau-facile-3-points)
- [Exercice 3-B — Formule de Leibniz, niveau difficile](#exercice-3-b--formule-de-leibniz-niveau-difficile-3-points)

**Type exercice 4 — Repère dans un pavé**
- [Exercice 4-A — Lire sur un pavé](#exercice-4-a--lire-sur-un-pavé-3-points)
- [Exercice 4-B — Un quadrilatère dans le pavé](#exercice-4-b--un-quadrilatère-dans-le-pavé-3-points)

---

# 🧊 Type exercice 1 — Vecteurs dans le cube

## Exercice 1-A — Centre de gravité et alignement (3 points)

$ABCDEFGH$ est un cube (base $ABCD$, face supérieure $EFGH$, avec $E$ au-dessus de $A$, $F$ au-dessus de $B$, $G$ au-dessus de $C$ et $H$ au-dessus de $D$).

On note $K$ le point tel que $\overrightarrow{KA}+\overrightarrow{KC}+\overrightarrow{KH}=\vec 0$ (centre de gravité du triangle $ACH$).

**a.** En introduisant le point $D$ dans chacun des trois vecteurs, démontrer que
$$\overrightarrow{DK}=\frac13\left(\overrightarrow{DA}+\overrightarrow{DC}+\overrightarrow{DH}\right).$$

**b.** Exprimer $\overrightarrow{DF}$ en fonction de $\overrightarrow{DA}$, $\overrightarrow{DC}$, $\overrightarrow{DH}$.

**c.** En déduire que $D$, $K$ et $F$ sont alignés, et préciser la position de $K$ sur $[DF]$.

<details>
<summary><b>✅ Corrigé de l'exercice 1-A</b></summary>

**a. (1 pt)** D'après la relation de Chasles :

$$\overrightarrow{KA}=\overrightarrow{KD}+\overrightarrow{DA},\qquad \overrightarrow{KC}=\overrightarrow{KD}+\overrightarrow{DC},\qquad \overrightarrow{KH}=\overrightarrow{KD}+\overrightarrow{DH}$$

En additionnant et en utilisant l'hypothèse :

$$3\overrightarrow{KD}+\overrightarrow{DA}+\overrightarrow{DC}+\overrightarrow{DH}=\vec0
\ \Longrightarrow\ 3\overrightarrow{KD}=-\left(\overrightarrow{DA}+\overrightarrow{DC}+\overrightarrow{DH}\right)$$

Comme $\overrightarrow{DK}=-\overrightarrow{KD}$ :

$$\boxed{\overrightarrow{DK}=\frac13\left(\overrightarrow{DA}+\overrightarrow{DC}+\overrightarrow{DH}\right)}$$

**b. (1 pt)** Par Chasles : $\overrightarrow{DF}=\overrightarrow{DA}+\overrightarrow{AB}+\overrightarrow{BF}$.

- $ABCD$ est un carré, donc $\overrightarrow{AB}=\overrightarrow{DC}$ ;
- les arêtes verticales du cube sont parallèles et de même longueur, donc $\overrightarrow{BF}=\overrightarrow{DH}$.

$$\boxed{\overrightarrow{DF}=\overrightarrow{DA}+\overrightarrow{DC}+\overrightarrow{DH}}$$

**c. (1 pt)** D'après a. et b. :

$$\overrightarrow{DK}=\frac13\overrightarrow{DF}$$

Les vecteurs $\overrightarrow{DK}$ et $\overrightarrow{DF}$ sont colinéaires : **$D$, $K$, $F$ sont alignés**. Le coefficient $\frac13$ est dans $[0;1]$ : $K$ appartient au segment $[DF]$, **au tiers de sa longueur à partir de $D$** ($DK=\frac13DF$).

</details>

---

## Exercice 1-B — Un parallélogramme dans le cube (3 points)

$ABCDEFGH$ est un cube (mêmes conventions que ci-dessus). On note $I$ le milieu de $[AE]$ et $J$ le milieu de $[CG]$.

**a.** Démontrer que $\overrightarrow{AI}=\overrightarrow{CJ}$.

**b.** En déduire que $\overrightarrow{IJ}=\overrightarrow{AC}$, puis la nature du quadrilatère $AIJC$.

**c.** On note $K$ le milieu de $[IC]$. Démontrer que $K$ est aussi le milieu de $[AJ]$.

<details>
<summary><b>✅ Corrigé de l'exercice 1-B</b></summary>

**a. (1 pt)** $I$ est le milieu de $[AE]$ : $\overrightarrow{AI}=\frac12\overrightarrow{AE}$.
$J$ est le milieu de $[CG]$ : $\overrightarrow{CJ}=\frac12\overrightarrow{CG}$.

Les arêtes verticales du cube sont parallèles, de même longueur et de même sens : $\overrightarrow{AE}=\overrightarrow{CG}$. Donc

$$\boxed{\overrightarrow{AI}=\overrightarrow{CJ}}$$

**b. (1 pt)** Par Chasles :

$$\overrightarrow{IJ}=\overrightarrow{IA}+\overrightarrow{AC}+\overrightarrow{CJ}=-\overrightarrow{AI}+\overrightarrow{AC}+\overrightarrow{CJ}$$

Comme $\overrightarrow{CJ}=\overrightarrow{AI}$ (question a.), il reste :

$$\boxed{\overrightarrow{IJ}=\overrightarrow{AC}}$$

On a $\overrightarrow{AI}=\overrightarrow{CJ}$ et $\overrightarrow{IJ}=\overrightarrow{AC}$ : les côtés opposés de $AIJC$ sont représentés par des vecteurs égaux, donc **$AIJC$ est un parallélogramme**.

*(C'est même un rectangle, car $(AE)$ est perpendiculaire au plan $(ABC)$, donc à $(AC)$.)*

**c. (1 pt)** $K$ est le milieu de $[IC]$ : $\overrightarrow{AK}=\frac12\left(\overrightarrow{AI}+\overrightarrow{AC}\right)$.

Soit $M$ le milieu de $[AJ]$. Alors, avec Chasles et $\overrightarrow{IJ}=\overrightarrow{AC}$ :

$$\overrightarrow{AM}=\frac12\overrightarrow{AJ}=\frac12\left(\overrightarrow{AI}+\overrightarrow{IJ}\right)=\frac12\left(\overrightarrow{AI}+\overrightarrow{AC}\right)$$

Donc $\overrightarrow{AK}=\overrightarrow{AM}$, d'où $K=M$ : **$K$ est aussi le milieu de $[AJ]$**.

*(C'est la propriété des diagonales d'un parallélogramme : elles se coupent en leur milieu.)*

</details>

---

# 📐 Type exercice 3 — Formule de Leibniz

## Exercice 3-A — Formule de Leibniz, niveau facile (3 points)

Soit $g$ la fonction définie sur $\mathbb{R}$ par $g(x)=x\,e^{2x}$.

**a.** Donner, pour tout entier $j$, la dérivée $j$-ième de $x\mapsto e^{2x}$ (sans démonstration).

**b.** À l'aide de la formule de Leibniz, démontrer que, pour tout entier $n\geqslant1$,
$$g^{(n)}(x)=2^{n-1}\,e^{2x}\,(2x+n).$$

**c.** Vérifier que la formule est aussi vraie pour $n=0$.

**d.** Calculer $g^{(8)}(0)$.

<details>
<summary><b>✅ Corrigé de l'exercice 3-A</b></summary>

**a. (0,5 pt)** Pour tout entier $j$ :
$$\left(e^{2x}\right)^{(j)}=2^j\,e^{2x}$$

**b. (1,5 pt)** Posons $u(x)=x$ et $v(x)=e^{2x}$. La formule de Leibniz donne :

$$g^{(n)}=\sum_{k=0}^{n}\binom nk\,u^{(k)}\,v^{(n-k)}$$

Ici $u'(x)=1$ et $u^{(k)}=0$ pour $k\geqslant2$. Seuls les termes $k=0$ et $k=1$ subsistent (ils existent bien car $n\geqslant1$) :

$$g^{(n)}(x)=\binom n0\,x\,2^ne^{2x}+\binom n1\times1\times2^{n-1}e^{2x}=2^ne^{2x}x+n\,2^{n-1}e^{2x}$$

Comme $2^n=2^{n-1}\times2$, on factorise par $2^{n-1}e^{2x}$ :

$$\boxed{g^{(n)}(x)=2^{n-1}\,e^{2x}\,(2x+n)}$$

**c. (0,5 pt)** Pour $n=0$, la formule donne
$$2^{-1}e^{2x}(2x+0)=\frac12\times2x\,e^{2x}=x\,e^{2x}=g(x)$$
qui est bien $g^{(0)}=g$ ✓.

*(Vérification supplémentaire pour $n=1$ : $g'(x)=e^{2x}+2xe^{2x}=e^{2x}(2x+1)$, et la formule donne $2^0e^{2x}(2x+1)$ ✓.)*

**d. (0,5 pt)** Avec $n=8$ et $x=0$ :
$$g^{(8)}(0)=2^{7}\,e^{0}\,(0+8)=128\times8=\boxed{1024}$$

</details>

---

## Exercice 3-B — Formule de Leibniz, niveau difficile (3 points)

Soit $h$ la fonction définie sur $\mathbb{R}$ par $h(x)=x^3e^{x}$.

**a.** Donner, pour tout entier $j$, la dérivée $j$-ième de $x\mapsto e^{x}$ (sans démonstration).

**b.** À l'aide de la formule de Leibniz, démontrer que, pour tout entier $n\geqslant3$,
$$h^{(n)}(x)=e^{x}\Big(x^3+3n\,x^2+3n(n-1)\,x+n(n-1)(n-2)\Big).$$

**c.** Vérifier que la formule est aussi vraie pour $n=2$, par un calcul direct de $h''$.

**d.** Calculer $h^{(6)}(0)$.

<details>
<summary><b>✅ Corrigé de l'exercice 3-B</b></summary>

**a. (0,5 pt)** Pour tout entier $j$ :
$$\left(e^{x}\right)^{(j)}=e^{x}$$

**b. (1,5 pt)** Posons $u(x)=x^3$ et $v(x)=e^{x}$. Les dérivées de $u$ sont :
$$u'(x)=3x^2,\qquad u''(x)=6x,\qquad u'''(x)=6,\qquad u^{(k)}=0\ \text{pour }k\geqslant4$$

Seuls les termes $k=0,1,2,3$ subsistent (ils existent bien car $n\geqslant3$). Comme toutes les dérivées de $v$ valent $e^x$ :

$$h^{(n)}(x)=e^{x}\left[\binom n0x^3+\binom n1\,3x^2+\binom n2\,6x+\binom n3\,6\right]$$

Or :

- $\binom n1\times3=3n$ ;
- $\binom n2\times6=\dfrac{n(n-1)}2\times6=3n(n-1)$ ;
- $\binom n3\times6=\dfrac{n(n-1)(n-2)}6\times6=n(n-1)(n-2)$.

$$\boxed{h^{(n)}(x)=e^{x}\Big(x^3+3n\,x^2+3n(n-1)\,x+n(n-1)(n-2)\Big)}$$

**c. (0,5 pt)** Calcul direct :

$$h'(x)=3x^2e^x+x^3e^x=e^x(x^3+3x^2)$$

$$h''(x)=e^x(x^3+3x^2)+e^x(3x^2+6x)=e^x(x^3+6x^2+6x)$$

La formule pour $n=2$ donne : $e^x\big(x^3+6x^2+3\times2\times1\,x+2\times1\times0\big)=e^x(x^3+6x^2+6x)$ : **identique** ✓.

**d. (0,5 pt)** Avec $n=6$ et $x=0$, seul le terme constant subsiste :
$$h^{(6)}(0)=e^0\times\big(6\times5\times4\big)=\boxed{120}$$

</details>

---

# 📦 Type exercice 4 — Repère dans un pavé

## Exercice 4-A — Lire sur un pavé (3 points)

$ABCDEFGH$ est un pavé droit avec $AB=4$, $AD=6$ et $AE=2$ (base $ABCD$, $E$ au-dessus de $A$, $F$ au-dessus de $B$, $G$ au-dessus de $C$, $H$ au-dessus de $D$). On le rapporte au repère orthonormé d'origine $A$ dont les axes portent $(AB)$, $(AD)$, $(AE)$.

**a.** Donner les coordonnées de $C$, $F$, $G$ et $H$.

**b.** $I$ est le milieu de $[BG]$ et $J$ celui de $[AH]$. Calculer leurs coordonnées et montrer que $(IJ)$ est parallèle à $(AB)$.

**c.** $K$ est le point tel que $\overrightarrow{AK}=\dfrac12\overrightarrow{AG}$. Démontrer que $K$ est le milieu de $[IJ]$, puis calculer la distance $AK$.

<details>
<summary><b>✅ Corrigé de l'exercice 4-A</b></summary>

**a. (0,5 pt)** Dans le repère $(A;\overrightarrow{AB},\overrightarrow{AD},\overrightarrow{AE})$ : $A(0;0;0)$, $B(4;0;0)$, $D(0;6;0)$, $E(0;0;2)$, d'où

$$C(4;6;0),\qquad F(4;0;2),\qquad G(4;6;2),\qquad H(0;6;2)$$

**b. (1,5 pt)** $B(4;0;0)$ et $G(4;6;2)$ donnent $I=\left(4;\,3;\,1\right)$.
$A(0;0;0)$ et $H(0;6;2)$ donnent $J=\left(0;\,3;\,1\right)$.

$$\overrightarrow{IJ}=(0-4;\,3-3;\,1-1)=(-4;0;0),\qquad \overrightarrow{AB}=(4;0;0)$$

On remarque $\overrightarrow{IJ}=-\overrightarrow{AB}$ : les vecteurs sont colinéaires, donc **$(IJ)$ est parallèle à $(AB)$**.

*(Les droites sont bien distinctes : $(AB)$ est l'ensemble des points d'ordonnée $0$ et de cote $0$, alors que $I$ a pour ordonnée $3$.)*

**c. (1 pt)** $\overrightarrow{AG}=(4;6;2)$, donc $\overrightarrow{AK}=\frac12\overrightarrow{AG}=(2;3;1)$ et $K(2;3;1)$.

Milieu de $[IJ]$ :
$$\left(\frac{4+0}2\,;\,\frac{3+3}2\,;\,\frac{1+1}2\right)=(2;3;1)=K$$

**$K$ est donc le milieu de $[IJ]$** (c'est aussi le centre du pavé).

Distance :
$$AK=\sqrt{2^2+3^2+1^2}=\boxed{\sqrt{14}}$$

</details>

---

## Exercice 4-B — Un quadrilatère dans le pavé (3 points)

$ABCDEFGH$ est un pavé droit avec $AB=5$, $AD=4$ et $AE=3$ (base $ABCD$, $E$ au-dessus de $A$, $F$ au-dessus de $B$, $G$ au-dessus de $C$, $H$ au-dessus de $D$). On le rapporte au repère orthonormé d'origine $A$ dont les axes portent $(AB)$, $(AD)$, $(AE)$.

**a.** Donner les coordonnées de $C$, $F$, $G$ et $H$.

**b.** Calculer les coordonnées des milieux de $[AG]$ et de $[BH]$. Que peut-on en déduire pour le quadrilatère $ABGH$ ?

**c.** Montrer que $ABGH$ est un carré, puis calculer son aire.

<details>
<summary><b>✅ Corrigé de l'exercice 4-B</b></summary>

**a. (0,5 pt)** Dans le repère $(A;\overrightarrow{AB},\overrightarrow{AD},\overrightarrow{AE})$ : $A(0;0;0)$, $B(5;0;0)$, $D(0;4;0)$, $E(0;0;3)$, d'où

$$C(5;4;0),\qquad F(5;0;3),\qquad G(5;4;3),\qquad H(0;4;3)$$

**b. (1,5 pt)**

Milieu de $[AG]$ : $\left(\dfrac{0+5}2\,;\,\dfrac{0+4}2\,;\,\dfrac{0+3}2\right)=\left(\dfrac52;\,2;\,\dfrac32\right)$.

Milieu de $[BH]$ : $\left(\dfrac{5+0}2\,;\,\dfrac{0+4}2\,;\,\dfrac{0+3}2\right)=\left(\dfrac52;\,2;\,\dfrac32\right)$.

Les deux milieux sont **confondus**. Les diagonales $[AG]$ et $[BH]$ du quadrilatère $ABGH$ ont le même milieu : **$ABGH$ est un parallélogramme**.

**c. (1 pt)** $\overrightarrow{AB}=(5;0;0)$ et $\overrightarrow{AH}=(0;4;3)$.

- Produit scalaire : $\overrightarrow{AB}\cdot\overrightarrow{AH}=5\times0+0\times4+0\times3=0$, donc $(AB)\perp(AH)$ : le parallélogramme a un angle droit, c'est un **rectangle**.
- Longueurs : $AB=5$ et $AH=\sqrt{0^2+4^2+3^2}=\sqrt{25}=5$.

Deux côtés consécutifs sont égaux : **$ABGH$ est un carré** de côté $5$, d'aire

$$\mathcal A=5^2=\boxed{25}$$

</details>

---

## 📊 Barème de chaque exercice

| Exercice | Thème | Points |
|---|---|:---:|
| 1-A | Centre de gravité, Chasles, alignement | 3 |
| 1-B | Égalité de vecteurs, parallélogramme, milieux | 3 |
| 3-A | Leibniz avec $xe^{2x}$ (2 termes) | 3 |
| 3-B | Leibniz avec $x^3e^{x}$ (4 termes) | 3 |
| 4-A | Coordonnées, milieux, parallélisme, distance | 3 |
| 4-B | Milieux, parallélogramme, carré (produit scalaire) | 3 |

---

## 🧑‍🏫 Notes pour le professeur

### Erreurs fréquentes à surveiller

| Exercice | Piège |
|---|---|
| 1-A | Oublier que $\overrightarrow{KD}=-\overrightarrow{DK}$ ; ne pas justifier $\overrightarrow{AB}=\overrightarrow{DC}$ et $\overrightarrow{BF}=\overrightarrow{DH}$ |
| 1-B | Écrire « $AIJC$ est un parallélogramme » sans avoir démontré les deux égalités de vecteurs |
| 3-A | Oublier de factoriser par $2^{n-1}$ ; confondre $2^n$ et $2^{n-1}$ |
| 3-B | Oublier un terme de la somme ($k=3$) ; se tromper sur $\binom n2\times6$ et $\binom n3\times6$ |
| 4-A | Conclure « parallèle » sans mentionner la colinéarité ; oublier la racine dans la distance |
| 4-B | Conclure « carré » avec un seul angle droit sans comparer deux côtés consécutifs |

### Progression conseillée

1. Faire d'abord **1-A, 3-A, 4-A** (niveau du devoir blanc).
2. Passer ensuite à **1-B, 3-B, 4-B** (un cran plus exigeants).
