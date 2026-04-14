_Reflection_
The reflection of a set $B$ about its origin, denoted by $\hat{B}$, is defined as 
$$\hat{B} = \{w|w=-b, b\in B\}$$
_Translation_
The traslation of a set $B$ by point $z=(z_1,z_2)$, denoted by $$(B)_z = \{ c \mid c = b + z,\ \text{for } b \in B \}$$
_Erosion_
$$A \ominus B = \{z \mid (B)_z \subseteq A\}
$$
_Dilation_
$$A \oplus B = \{z \mid (\hat{B})_z \cap A \neq \emptyset\}
$$
_Opening_
$$A \circ B = (A \ominus B) \oplus B$$
![[Pasted image 20260410212706.png]]
_Closing_
$$A \bullet B = (A \oplus A) \ominus B$$
![[Pasted image 20260410212724.png]]
