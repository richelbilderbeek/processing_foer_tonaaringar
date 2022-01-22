# Sinus och cosinus 1: tecken.

I den här lektionen ska vi rita en sinus och en cosinus.

![Elite](Elite.jpg)

\sidbrytning

## Sinus och Cosinus 1: Kommando 1

Skriv denna kod över:

```c++
float x = 0;

void setup()
{
  storlek (314, 200);
}

void draw()
{
  final float y = sin(x);
  punkt (x, y);
  x = x + 1;
}
```

Vad ser du?

![Solglasögon](EmojiSunglasses.png) | 314 är ungefär hundra gånger talet pi
:-----------------:|:----------------------------- -------- -------:

\sidbrytning

## Sinus och cosinus 1: lösning 1

![Sinus och cosinus 1: lösning 1](SinusEnCosine1_1.png)

Du kommer att se en sorts prickad linje längst upp.

\sidbrytning

## Sinus och Cosinus 1: Kommando 2

 * Flytta den prickade linjen nedåt. Gör detta genom att lägga till halva höjden med `y`

![Solglasögon](EmojiSunglasses.png) | Tips: det är smart att sätta parenteser runt `höjd / 2`
:-----------------:|:----------------------------- -------- -------:

![Sinus och cosinus 1: kommando 2](SinusEnCosine1_2.png)

\sidbrytning

## Sinus och cosinus 1: lösning 2

```c++
float x = 0;

void setup()
{
  storlek (314, 200);
}

void draw()
{
  slutlig float y = sin(x) + (höjd / 2);
  punkt (x, y);
  x = x + 1;
}
```

![Solglasögon](EmojiSunglasses.png) | Fästena hjälper datorn att veta ordningen på en beräkning
:-----------------:|:---------------------- ------- :

![Solglasögon](EmojiSunglasses.png) | En sinusvåg är formad som en våg som svänger mellan -1 och 1
:-----------------:|:----------------------------- -------- -------:

\sidbrytning

## Sinus och cosinus 1: uppgift 3

 * Ersätt `sin(x)` med `(sin(x) * 50)`

![Sinus och cosinus 1: kommando 3](SinusEnCosine1_3.png)

![Solglasögon](EmojiSunglasses.png) | Parentes är viktigt!
:-----------------:|:----------------------------- -------- -------:

\sidbrytning

## Sinus och cosinus 1: lösning 3

Du kommer nu att se ett mönster.

![Sinus och cosinus 3: kommando 2](SinusEnCosine1_3.png)

```c++
float x = 0;

void setup()
{
  storlek (314, 200);
}

void draw()
{
  slutlig float y = (sin(x) * 50) + (höjd / 2);
  punkt (x, y);
  x = x + 1;
}
```

![Solglasögon](EmojiSunglasses.png) | Det är en röra, eftersom vi blandar ungefär 100 bihålor
:-----------------:|:----------------------------- -------- -------:

![Solglasögon](EmojiSunglasses.png) | `*50` gör att sinus förstoras femtio gånger
:-----------------:|:----------------------------- -------- -------:

## Sinus och cosinus 1: uppgift 4

 * Ersätt `sin(x)` med `sin(x / 100)`

![Sinus och cosinus 1: kommando 4](SinusEnCosine1_4.png)


\sidbrytning

## Sinus och cosinus 1: lösning 4

Du ser nu en våg: en sinus!.

![Sinus och cosinus 1: kommando 4](SinusEnCosine1_4.png)

```c++
float x = 0;

void setup()
{
  storlek (314, 200);
}

void draw()
{
  slutlig float y = (sin(x / 25) * 50) + (höjd / 2);
  punkt (x, y);
  x = x + 1;
}
```

## Sinus och Cosinus 1: Kommando 5

 * Ersätt `sin(x)` med `cos(x)`

![Sinus och cosinus 1: kommando 5](SinusEnCosine1_5.png)


\sidbrytning

## Sinus och cosinus 1: lösning 5

Du ser nu en våg: en sinus!.

![Sinus och cosinus 1: kommando 5](SinusEnCosine1_5.png)

```c++
float x = 0;

void setup()
{
  storlek (314, 200);
}

void draw()
{
  slutlig float y = (sin(x / 25) * 50) + (höjd / 2);
  punkt (x, y);
  x = x + 1;
}
```


![Solglasögon](EmojiSunglasses.png) | `x / 25` ser till att vi går 25x lugnare genom sinus
:-----------------:|:---------------------- ------- :

\sidbrytning

## Sinus och cosinus 1: Slutuppgift

 * Rita både sinus och cosinus
 * Få varje våg att gå upp och ner en gång
 * Rita cosinus röd, sinus blå

![Sinus och cosinus 1: Slutuppgift](SinusEnCosinus1_End assignment.png)