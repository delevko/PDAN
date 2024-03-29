Promień od obserwatora o kierunku (-1, 0, 1) pada na płaszczyznę XY w środku układu współrzędnych. Płaszczyźnie nadana jest monochromatyczna tekstura T o wzorze: T(x,y) = \sqrt{|x+1|}. Wyznacz wyliczony wektor normalny n dla powyższego promienia, gdy T jest użyta jako mapa wysokości, i wykorzystany jest:
===

_Obserwacja: Możemy zignorować współrzędną y, ponieważ jest ona wyzerowana w wektorze promienia. Problem upraszcza się do dwuwymiarowego promienia (-1, 1) i funkcji T(x) = \sqrt{|x+1|}._

Bump mapping
---

![derivative](http://bit.ly/2IquHvT)

Wektor linii (2, 1), więc normalny (1, -2).

Najprostsze mapowanie paralaksy
---

tg(\theta) = -1

T(0) = 1

(u',v') = (u,v) - T(0) \* tg(\theta) \* d = (0,0) - 1 * (-1) * (-1, 1) = (-1, 1)

Pochodna w -1 dąży do nieskończoności więc normalny to (1,0)

Dokładne śledzenie promieni paralaksy
---

-x = \sqrt(|x+1|)

x^2 = |x+1|

x^2 = x+1

x = 1/2 - \sqrt(5)/2

T'(1/2 - \sqrt(5)/2) = (1 + \sqrt(5))/4

Wektor linii (1, (1 + \sqrt(5))/4), więc normalny ((1 + \sqrt(5))/4, -1).
