#Limites

>[!info]
>El **límite** describe **a qué valor se aproxima una función cuando la variable se acerca a un punto**, aunque nunca llegue exactamente a ese punto.

# Definición

Un limite lo podemos definir como el valor al cual se aproxima la variable independiente de una función a un valor $a$, la aproximación se hace tanto desde la izquierda como la derecha.$$\lim_{x \to a} f(x) = L \leftrightarrow \lim_{x \to a^-} f(x) = L \text{ and } \lim_{x \to a^+} f(x) = L \tag{1}$$
- $c^-$ : Indica que el limite por la izquierda cuando la función tiende a $c$.
- $c^+$ : Indica que el limite por la derecha cuando la función tiende a $c$.

---
# Definición precisa

Tenemos dos componentes importantes para formalizar nuestra definición.

- $\epsilon$: representa que tanto queremos que nuestra $f(x)$ se acerca a $L$ 
- $\delta$: representa que tan cerca debe estar $x$ de $a$

Tenemos que de (1):

1. Para todo $\epsilon > 0$ existe un valor  $\delta > 0$, tal que:
	- $0<|x-a|<\delta$
	- $0 < |f(x) -L|<\epsilon$


![[delta_epsilon_limit_definition.png]]