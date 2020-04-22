Budujemy internetowy translator chmurowy
=========================================

W tym tutorialu, naszym celem będzie zbudowanie internetowego translatora. Będzie to internetowa aplikacja, umożliwiająca wpisywanie tekstu przez użytkownika, który następnie będzie tłumaczony na wskazany przez użytkownika język. Dodatkowo aplikacja będzie generowała plik audio dla wskazanego tekstu.

W tym celu zostaną wykorzystane trzy usługi AI chmurowe:
- **Amazon Comprehend** - usługa, którą wykorzystamy aby wykrywać jezyk w jakim zostął wpisany przez użytkownika tekst.
- **Amazon Translate** - usługa, która będzie dokonywała inteligentnego tłumaczenia z języka na język.
- **Amazon Polly** - usługa text-to-speech, która będzie konwertowała tekst na audio.

== Kroki ==
**1** TODO
**2** TODO


Phase 0: Environment setup
-----
1. Sign into the AWS Console and choose `us-east-1` (N. Virginia) region.
2. Open Cloud9 service and create new environment. You can use default settings.
3. Download all needed resources using following commands.
