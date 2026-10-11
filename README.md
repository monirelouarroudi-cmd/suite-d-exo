**c. (0,5 pt)** Calcul direct :
$$f'(x)=2xe^{-x}-x^2e^{-x}=e^{-x}(2x-x^2)=-e^{-x}(x^2-2x)$$

La formule pour $n=1$ donne $(-1)^1e^{-x}\big(x^2-2x+1\times0\big)=-e^{-x}(x^2-2x)$ : **identique** ✓.

**d. (0,5 pt)** Avec $n=10$ et $x=0$ :
$$f^{(10)}(0)=(-1)^{10}e^{0}\big(0-0+10\times9\big)=\boxed{90}$$

</details>

---

## Exercice 4 — Lire sur un pavé (3 points)

$ABCDEFGH$ est un pavé droit avec $AB=6$, $AD=4$ et $AE=2$ (base $ABCD$, $E$ au-dessus de $A$, $F$ au-dessus de $B$, $G$ au-dessus de $C$, $H$ au-dessus de $D$). On le rapporte au repère orthonormé d'origine $A$ dont les axes portent $(AB)$, $(AD)$, $(AE)$.

**a.** Donner les coordonnées de $C$, $F$, $G$ et $H$.

**b.** $I$ est le milieu de $[EH]$ et $J$ celui de $[BC]$. Calculer leurs coordonnées et montrer que $(IJ)$ est parallèle à $(BE)$.

**c.** $K$ est le point tel que $\overrightarrow{AK}=\dfrac12\overrightarrow{AG}$. Démontrer que $K$ est le milieu de $[IJ]$.

<details>
<summary><b>✅ Corrigé de l'exercice 4</b></summary>

**a. (0,5 pt)** Dans le repère $(A;\overrightarrow{AB},\overrightarrow{AD},\overrightarrow{AE})$ (orthonormé, avec les longueurs réelles) : $A(0;0;0)$, $B(6;0;0)$, $D(0;4;0)$, $E(0;0;2)$, d'où

$$C(6;4;0),\qquad F(6;0;2),\qquad G(6;4;2),\qquad H(0;4;2)$$

**b. (1,5 pt)** $E(0;0;2)$ et $H(0;4;2)$ donnent $I=\left(0;\,2;\,2\right)$.
$B(6;0;0)$ et $C(6;4;0)$ donnent $J=\left(6;\,2;\,0\right)$.

$$\overrightarrow{IJ}=(6;0;-2),\qquad \overrightarrow{BE}=(0-6;\,0-0;\,2-0)=(-6;0;2)$$

On remarque $\overrightarrow{BE}=-\overrightarrow{IJ}$ : les vecteurs sont colinéaires, donc **$(IJ)$ est parallèle à $(BE)$**.

*(Les droites sont bien distinctes : $(BE)$ est contenue dans le plan $y=0$, alors que $I$ a pour ordonnée $2$.)*

**c. (1 pt)** $\overrightarrow{AG}=(6;4;2)$, donc $\overrightarrow{AK}=\frac12\overrightarrow{AG}=(3;2;1)$ et $K(3;2;1)$.

Milieu de $[IJ]$ :
$$\left(\frac{0+6}2\,;\,\frac{2+2}2\,;\,\frac{2+0}2\right)=(3;2;1)=K$$

**$K$ est donc le milieu de $[IJ]$** (c'est aussi le centre du pavé).

</details>

---

## Exercice 5 — Problème : un robot (6 points)

Dans un repère $(O;\vec\imath,\vec\jmath,\vec k)$, un robot part de $O(0;0;0)$ et avance **par pas** : chaque pas est une translation de vecteur $\vec\imath$, $\vec\jmath$ ou $\vec k$. Il doit rejoindre $P(3;2;1)$. Un chemin est noté par la liste de ses pas ; par exemple $\vec\imath\,\vec\imath\,\vec\jmath\,\vec k\,\vec\imath\,\vec\jmath$.

### Partie A — géométrie

**a.** Justifier qu'après un chemin comportant $a$ pas $\vec\imath$, $b$ pas $\vec\jmath$ et $c$ pas $\vec k$, le robot est au point $(a;b;c)$. Combien de pas de chaque sorte comporte un chemin de $O$ à $P$ ?

**b.** Après trois pas, le robot peut être en $R(3;0;0)$, $S(0;3;0)$, $T(0;0;3)$, $M(2;1;0)$, $N(0;2;1)$ ou $L(1;0;2)$. Démontrer que $R$, $S$, $T$ ne sont pas alignés, puis que $M$, $N$ et $L$ appartiennent au plan $(RST)$.

### Partie B — dénombrement

**a.** Combien de chemins mènent de $O$ à $P$ ? (On pourra choisir d'abord la place des pas $\vec\imath$, puis celle des pas $\vec\jmath$.)

**b.** Combien de ces chemins passent par le point $Q(1;1;1)$ ?

**c.** Combien l'évitent ?

**d.** Combien de chemins passent par le point $U(2;0;1)$ ?

> 🌟 **Question bonus (non notée).** Un chemin peut-il passer à la fois par $Q$ et par $U$ ? Justifier.

<details>
<summary><b>✅ Corrigé de l'exercice 5</b></summary>

### Partie A — géométrie

**a. (1 pt)** Chaque pas ajoute un vecteur : après $a$ pas $\vec\imath$, $b$ pas $\vec\jmath$ et $c$ pas $\vec k$ (dans n'importe quel ordre, l'addition vectorielle étant commutative), le robot est en $M$ tel que
$$\overrightarrow{OM}=a\,\vec\imath+b\,\vec\jmath+c\,\vec k$$
donc $M(a;b;c)$.

Pour atteindre $P(3;2;1)$, on doit avoir $a=3$, $b=2$, $c=1$ (unicité des coordonnées) : un chemin de $O$ à $P$ comporte **3 pas $\vec\imath$, 2 pas $\vec\jmath$ et 1 pas $\vec k$**, soit 6 pas en tout.

**b. (1,5 pt)**

*$R,S,T$ non alignés.* $\overrightarrow{RS}=(-3;3;0)$ et $\overrightarrow{RT}=(-3;0;3)$. Si ces vecteurs étaient colinéaires, on aurait $\overrightarrow{RT}=\lambda\overrightarrow{RS}$, d'où pour la troisième coordonnée $3=\lambda\times0$ : impossible. Les vecteurs ne sont pas colinéaires : **$R,S,T$ ne sont pas alignés**, ils définissent un plan.

*$M,N,L\in(RST)$.* Un point $X$ appartient à $(RST)$ si et seulement s'il existe $\alpha,\beta$ tels que $\overrightarrow{RX}=\alpha\overrightarrow{RS}+\beta\overrightarrow{RT}=(-3\alpha-3\beta\,;\,3\alpha\,;\,3\beta)$.

| Point | $\overrightarrow{RX}$ | $\alpha$ (2ᵉ coord.) | $\beta$ (3ᵉ coord.) | Vérification 1ʳᵉ coord. $-3\alpha-3\beta$ |
|---|---|---|---|---|
| $M(2;1;0)$ | $(-1;1;0)$ | $\frac13$ | $0$ | $-1$ ✓ |
| $N(0;2;1)$ | $(-3;2;1)$ | $\frac23$ | $\frac13$ | $-2-1=-3$ ✓ |
| $L(1;0;2)$ | $(-2;0;2)$ | $0$ | $\frac23$ | $-2$ ✓ |

Les trois points appartiennent donc au plan $(RST)$.

> 💡 **Autre façon de voir :** le plan $(RST)$ a pour équation $x+y+z=3$, et après trois pas, la somme des coordonnées vaut toujours $3$.

### Partie B — dénombrement

**a. (1 pt)** Un chemin comporte 6 pas. On choisit les places des 3 pas $\vec\imath$ parmi 6 : $\binom63=20$ façons. Parmi les 3 places restantes, on choisit celles des 2 pas $\vec\jmath$ : $\binom32=3$ façons. Le pas $\vec k$ occupe la dernière place.

$$20\times3=\boxed{60\text{ chemins}}$$

**b. (1 pt)** Passer par $Q(1;1;1)$ se fait forcément au bout de 3 pas ($1+1+1=3$) :

- de $O$ à $Q$ : un pas $\vec\imath$, un $\vec\jmath$, un $\vec k$ dans un ordre quelconque, soit $3!=6$ chemins ;
- de $Q$ à $P$ : $\overrightarrow{QP}=(2;1;0)$, donc 2 pas $\vec\imath$ et 1 pas $\vec\jmath$ : $\binom32=3$ chemins.

Par le principe multiplicatif : $6\times3=\boxed{18\text{ chemins}}$.

**c. (0,5 pt)** Chemins évitant $Q$ : $60-18=\boxed{42}$.

**d. (1 pt)** Passer par $U(2;0;1)$ se fait au bout de 3 pas :

- de $O$ à $U$ : 2 pas $\vec\imath$ et 1 pas $\vec k$ : $\binom31=3$ chemins ;
- de $U$ à $P$ : $\overrightarrow{UP}=(1;2;0)$, donc 1 pas $\vec\imath$ et 2 pas $\vec\jmath$ : $3$ chemins.

$$3\times3=\boxed{9\text{ chemins}}$$

**🌟 Bonus.** Non : $Q$ et $U$ sont deux points **distincts** atteints tous deux après exactement 3 pas. Le robot ne peut pas être en deux endroits différents au bout de 3 pas : aucun chemin ne passe par les deux (0 chemin).

</details>

---

## 📊 Récapitulatif du barème

| Exercice | Thème | Points | Note élève |
|---|---|:---:|:---:|
| 1 | Vecteurs, centre de gravité, alignement dans le cube | 3 | … |
| 2 | Python et dénombrement (parties, complémentaire) | 5 | … |
| 3 | Dérivées successives, formule de Leibniz | 3 | … |
| 4 | Repère orthonormé dans un pavé | 3 | … |
| 5 | Problème : robot (géométrie + dénombrement) | 6 | … |
| | **Total** | **20** | … |

---

## 🧑‍🏫 Notes pour le professeur

### Rappels nécessaires à la correction

- **Chasles :** $\overrightarrow{AB}=\overrightarrow{AC}+\overrightarrow{CB}$ ; centre de gravité $G$ de $ABC$ : $\overrightarrow{GA}+\overrightarrow{GB}+\overrightarrow{GC}=\vec0$.
- **Leibniz :** $(uv)^{(n)}=\displaystyle\sum_{k=0}^{n}\binom nk\,u^{(k)}v^{(n-k)}$ ; $\ (e^{ax})^{(j)}=a^je^{ax}$.
- **Dénombrement :** principe multiplicatif, $\dbinom nk=\dfrac{n!}{k!\,(n-k)!}$, passage au complémentaire.

### Erreurs fréquentes à surveiller

| Exercice | Piège |
|---|---|
| 1 | Oublier que $\overrightarrow{KB}=-\overrightarrow{BK}$ ; ne pas justifier $\overrightarrow{AD}=\overrightarrow{BC}$ et $\overrightarrow{DH}=\overrightarrow{BF}$ |
| 2 | Confondre $10^3$ (tous les codes) et $\binom{10}{3}$ (codes croissants) ; ne pas expliquer le rapport $\frac16=\frac1{3!}$ |
| 3 | Oublier que $u^{(k)}=0$ pour $k\geqslant3$ ; se tromper sur $(-1)^{n-1}$ ; ne pas factoriser |
| 4 | Conclure « parallèle » sans mentionner la colinéarité des vecteurs |
| 5 | Confondre « passer par $Q$ » et « finir en $Q$ » ; oublier de multiplier les deux étapes (avant / après le point) |

### Grille d'observation

- [ ] Rédige proprement chaque démonstration vectorielle
- [ ] Sait lire un programme et le traduire en dénombrement
- [ ] Maîtrise le passage au complémentaire
- [ ] Applique correctement la formule de Leibniz
- [ ] Lit et calcule des coordonnées dans un repère de l'espace
- [ ] Décompose un chemin en étapes (principe multiplicatif)
- [ ] Gère son temps sur 1 h 45
- [ ] Erreurs surtout calculatoires
- [ ] Erreurs surtout méthodologiques / de rédaction
