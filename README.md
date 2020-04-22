Budujemy internetowy translator chmurowy
=========================================

W tym tutorialu, naszym celem będzie zbudowanie internetowego translatora. Będzie to internetowa aplikacja, umożliwiająca wpisywanie tekstu przez użytkownika, który następnie będzie tłumaczony na wskazany przez użytkownika język. Dodatkowo aplikacja będzie generowała plik audio dla wskazanego tekstu.

W tym celu zostaną wykorzystane trzy usługi AI chmurowe:
- Amazon Comprehend - usługa, którą wykorzystamy aby wykrywać jezyk w jakim zostął wpisany przez użytkownika tekst.
- Amazon Translate - usługa, która będzie dokonywała inteligentnego tłumaczenia z języka na język.
- Amazon Polly - usługa text-to-speech, która będzie konwertowała tekst na audio.
