# Jak to działa

Prezentacja jest napisana w [Asciidoctor](https://docs.asciidoctor.org/asciidoc/latest/syntax-quick-reference/) a potem przez wtyczkę [asciidoctor-revelajs](https://docs.asciidoctor.org/reveal.js-converter/latest/), konwertowana do prezentacji w HTML5 (z wykorzystaniem [Reveal.JS](https://revealjs.com/) )

## To jak to działa?

By wygenerować prezentację, wystarczy polecenie:

    ./gradlew asciidoctorRevealJs

By jednocześnie modyfikować i oglądać zmiany:

    ./gradlew asciidoctorRevealJs liveReload --livereload-verbose