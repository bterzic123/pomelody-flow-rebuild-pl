# Audyt wzrostu — pomelody

**Na żywo:** https://bterzic123.github.io/pomelody-flow-rebuild-pl/
**Tylko prototyp:** https://bterzic123.github.io/pomelody-flow-rebuild-pl/?view=proto
**Wersja angielska:** https://bterzic123.github.io/pomelody-flow-rebuild/

pomelody pyta każdą rodzinę o imię dziecka, rok urodzenia i to, czego potrzebuje, a potem pokazuje wszystkim to samo „Try pomelody for 7 days for free”. Ten audyt przebudowuje pierwsze uruchomienie tak, żeby każda rodzina widziała swoje dziecko na ekranie, na którym płaci, w designie pomelody i w jej cenach.

## Pięć pomysłów

| # | Pomysł | Oczekiwany efekt |
| :-- | :-- | :-- |
| 1 | Zdejmijcie logowanie z pierwszego ekranu | CR +5–10% · ARPU +10–17% |
| 2 | Wpiszcie imię dziecka i jego wybory w nagłówek paywalla | CR +15–20% |
| 3 | Niech ładowanie i kolejny ekran powtórzą odpowiedzi | CR +10–15% |
| 4 | Plany i okres próbny na pierwszym ekranie paywalla | CR +5–15% · ARPU +10–15% |
| 5 | Zapytajcie o powiadomienia, gdy rodzina jest już w aplikacji | CR +10–15% |

Zakresy efektów to oczekiwany wpływ na podstawie analiz i testów A/B Adapty w aplikacjach subskrypcyjnych, a nie zmierzony wzrost dla pomelody.

## Skąd pochodzą dane

Ekrany, teksty, ilustracje, 7 dni za darmo i przypomnienie 2 dni przed końcem pochodzą z aplikacji pomelody na iOS nagranej 12 listopada 2026. Ceny w złotych, ocena (4,8 z 1,3 tys. ocen) i cytowana recenzja pochodzą z karty w polskim App Store. Reklamy i daty pochodzą z Meta, według AppMagic. Nic na stronie nie jest wymyślone.

## Uruchomienie lokalne

```bash
python3 -m http.server 8000
```

Następnie otwórz http://localhost:8000.

Przygotowane przez Adapty. [Umów demo](https://calendly.com/d/cty4-37z-zqj)
