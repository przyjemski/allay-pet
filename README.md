# Allay Pet 🩵

Allay z Minecrafta jako animowany pet. Podczas pracy obsługuje command block.

**[Dodaj Allaya / Install Allay](https://przyjemski.github.io/allay-pet/)**

![Allay przy command blocku](working.gif)

## Jak dodać

1. Zainstaluj lub zaktualizuj aplikację ChatGPT desktop / Codex z obsługą Pets.
2. Otwórz [stronę instalacji](https://przyjemski.github.io/allay-pet/) i kliknij **Dodaj Allaya**.
3. Zezwól przeglądarce na otwarcie aplikacji, następnie potwierdź dodanie w jej oknie instalacyjnym.
4. W ustawieniach **Pets** wybierz Allaya. Jeśli jest ukryty, użyj **Show pet / Pokaż peta** lub `/pet`.

Przycisk korzysta z [oficjalnego linku instalacyjnego](https://learn.chatgpt.com/docs/app/commands#pets) i przekazuje `spriteVersionNumber=2`. Funkcja musi być dostępna w używanej wersji aplikacji.

Jeśli przycisk nie reaguje, pobierz [allay.png](https://raw.githubusercontent.com/przyjemski/allay-pet/main/allay.png) i dodaj plik przez **Upload pet**, jeżeli Twój importer obsługuje v2. Gdy importer wymaga dokładnie **1536×1872**, użyj [wersji v1](allay-legacy-v1.png). Ma te same dziewięć animacji, ale bez dodatkowych szesnastu kierunków patrzenia. Sama kopia pliku w dowolnym folderze nie instaluje peta.

## Co potrafi

- Spokojnie unosi się, lata w lewo i prawo, macha i podskakuje.
- Reaguje na błąd, czeka na odpowiedź i sprawdza wynik.
- Przy aktywnej pracy obsługuje command block.
- Wersja v2 rozgląda się w szesnastu kierunkach.

![Podgląd wszystkich animacji](preview.gif)

## Pliki

| Plik | Zawartość |
| --- | --- |
| `allay.png` | Główny arkusz v2: 1536×2288, 73 klatki, przezroczyste tło |
| `allay-legacy-v1.png` | Zapasowy arkusz v1: 1536×1872, 57 klatek |
| `working.gif` | Podgląd pracy przy command blocku |
| `preview.gif` | Podgląd dziewięciu animacji |
| `contact-sheet.png` | Wszystkie klatki z etykietami |
| `pet.json` | Opis pliku i układu klatek; plik informacyjny |
| `SHA256SUMS` | Sumy kontrolne pobieranych plików |

## English

An animated Minecraft-inspired Allay companion that operates a command block while a task is running. Open the [install page](https://przyjemski.github.io/allay-pet/), choose **Dodaj Allaya**, allow the browser to open the desktop app, and confirm the pet installation there. Select Allay in **Pets**. The install flow must be enabled in your app version. If needed, download the PNG manually; use the v1 fallback only when your importer requires 1536×1872.

Artwork created with AI and refined as a fan project. Not affiliated with Mojang, Microsoft or OpenAI. Minecraft and Allay belong to their respective rights holders.
