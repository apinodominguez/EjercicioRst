
======================
Esto é unha cabeceira
======================

cabeceira h1
*************

Título h2
=========

Título h3
----------

Título h4
++++++++++

Marcado dentro do texto
++++++++++++++++++++++++
Escribimos texto en varias liñas e esto forma un paragrafo,
Lembrade que o taabulado é importante para que o entenda sphinx. Dentro de texto podemos mediante *cursiva*, ou
**negriña** e ``dobles comiñas para o codigo``.

Listas non numeradas
++++++++++++++++++++
* Podemos facer listas
* De distintos elementos
  utilizando o *

Listas numeradas
+++++++++++++++++++
1. Outra lista numerada
2. utilizando o número seguido do punto

#. Seguimos numerado listas
#. Neste caso utilizamos #.

Cun novo paragrafo no medio comeza a numeración

#. Nova lista

Sublistas
++++++++++
* Lista
* Con elementos

    * En novas  sublistas
    * Con distintos niveis
* E subniveis

Definicions
++++++++++++
Termino
    Definición do termino, mediante tabulacion

    Pode ter varios paragrafos
Outro Termino
    Coa súa definición

Saltos de liña
+++++++++++++++
| Estas liñas se mostraran
| Un texto máis grande
| cos saltos de liña marcados
| de forma exacta

Bloques de texto literales
+++++++++++++++++++++++++++

O texto normal de paragrafo. Otexto que se mostra a continuación sería un bloque literal::

    import sys

    class minhaClase:
        # Por facer

Continuamos o texto ao mesmo nivel de paragrafo a continuación

>>> 2 + 2
4

+-------------------------+----------------+-------------+--------------+
| Cabeceira fila columna1 | Cabeceira 2    | Cabeceira 3 | Cabeceira 4  |
| Pode usar varias liñas  |                |             |              |
+=========================+================+=============+==============+
| Fila 1, columna 1       | Fila 1, col2   | tu madre    | Escoria      |
+-------------------------+----------------+-------------+--------------+

Listas
+++++++

==========    ==========    ==========
Lista 1       Lista 2       Lista 3
==========    ==========    ==========
Elemento 1    Elemento 2    Elemento 3
Elemento 4    Elemento 6    Elemento 7
Elemento 5    Elemento 8    Elemento 9
==========    ==========    ==========

Enlaces
++++++++
.. _Spiderman comic : https://readcomiconline.to/Comic/The-Amazing-Spider-Man-2018/Issue-37?id=165937#17

Os enlaces no e necesario marcarlos https://readcomiconline.to/Comic/The-Amazing-Spider-Man-2018/Issue-37?id=165937#17
salvo que queiramos etiqueta para o enlace o `Spiderman <https://readcomiconline.to/Comic/The-Amazing-Spider-Man-2018/Issue-37?id=165937#17>`_

Outra forma de acceder o `Spiderman comic`_.


