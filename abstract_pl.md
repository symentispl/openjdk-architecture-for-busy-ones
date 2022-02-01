Jakże Vspaniała Maszyna

Java, Scala, Kotlin, Groovy, Clojure, Frege. Różnią się paradygmatami,
systemem typów (lub ich brakiem) czy podejściem do problemów współbieżności. Łączy je jednak środowisko, w którym działają.
Poznajcie JVM (Jakże Vspaniała Maszynę). Być może nie jest doskonała,
na wyposażeniu leży gruba warstwa kurzu, tryby zardzewiały, a z zewnątrz
prezentuję się jak Polonez (dla tych, co nie wiedzą, to samochód z czasów PRL). Jednak mimo wszystkich swoich wad i wieku (ponad 25 lat),
najbardziej popularna i (nie boję się tego powiedzieć), zaawansowana maszyna do zadań specjalnych, ale i też tych codziennych i trywialnych.

Podczas tej prezentacji wjedziemy na kanał z naszą maszyną i zobaczymy, co się kryje pod maską. Pokażemy, co się dzieje z waszym kodem. Od momentu kompilacji do bytecode do momentu, kiedy wasz kod zostanie zoptymalizowany do postaci maszynowej. Zaczniemy od inicjalizacji maszyny wirtualnej, by, potem zobaczyć jak ładowany jest i weryfikowany bytecode, jak działa interpreter, kiedy do gry wchodzi JIT (just-in-time compiler) i jakie zadanie ma do wykonania GC (garbage collector).
Aby jednak nie przynudzać was diagramami, pełnymi kształtów, strzałek i przypisów, zabierzemy was w podróż wewnątrz OpenJDK, jednej z implementacji JVM. Pokażemy, jak poszczególne komponenty JVM mają się do kodu C++ (w którym jest napisana większość OpenJDK).

Zabawy i "aha" momentów będzie co niemiara. Czy uczyni to z was lepszych ludzi? Śmiemy wątpić. Jednak świadomy inżynier powinien rozumieć jeden poziom abstrakcji poniżej tego, z którym styka się na co dzień.