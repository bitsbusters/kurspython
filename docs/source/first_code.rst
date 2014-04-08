..  _first_code:

Pierwszy kod
============

Kiedy myślałem jak powinno się pisać takie tutoriale najpierw chciałem wam zrobić wielkie wprowadzenie do programowania.
Zaczynając od typów języków, przez język C aż do assemblera. Potem pomyślałem jednak, że to zupełnie niepotrzebne.

Hello world!
------------

Dlatego też mając na uwadzę wasz głód programowania zaczniemy od przysłowiowego hello world!

Jak się to robi w Pythonie?

>>> print "Hello world!"
Hello world!

.. hint:: ">>>" oznaczają linie kodu wykoywane w interaktywnym terminalu, linie bez to efekt działania.

.. seealso:: O tym czym jest interaktywny terminal i jak go zainstalować piszę tu :ref:`iteractive_shell`.

Możesz też napisać plik np. **hello.py** z tą linijką kodu, a następnie wykonać go **python hello.py**.
Efekt wykonania naszego skryptu powinien być dokładnie taki sam jak w przypadku shella (terminala).

Zmienne
-------

Kolejny kod który napiszemy będzie wykorzystywał zmienne. Spróbujmy umieścić w zmiennych swoje imię oraz wiek i napisać nieco rozszerzoną wersje poprzedniego programu.

.. code-block:: python
   :linenos:

   name = 'Marcin'
   age = 26
   print u'Hello {0}, masz już {1:d} lat!".format(name, age)
   
O formatowaniu tekstu zamierzam napisać jeszcze osobny dział, tak aby wprowadzić was do rozbieżności midzy różnymi wersjami pythona oraz zaawansowanymi rzeczami. Na razie podstawy.

Dla tych którzy widzieli już kiedyś kod napisany w innym języku w oczy się rzuca brak jakichkolwiek funkcji, bloków kodu jak begin..end w pascalu itp. Również na uwagę zasługuje fakt iż nasze zmienne nie są nigdzie deklarowane a po prostu w pewnym miejscu kodu mamy ustawianą wartość. To wszystkie jest zaletą pythona który dynamicznie zajmuje pamięć dla zmiennych i rozpoznaje jakiego są one typu.

.. warning:: Czym jest tajemnicze u"" na początku napisu powiem w osobnym dziale na temat różnych dziwnych własnoci pythona.

