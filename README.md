### Cześć, tu Bartek 👋

**Inżynier drogowiec, nie programista.** Prowadzę małe biuro projektowe na Pomorzu (RedRoad, Gdańsk), w którym projektujemy drogi. Od marca 2026 robię to razem z AI. Kod pisze model, a ja wymagam, sprawdzam i decyduję. Amator, ale już co nieco ogarniam.

#### 🛣️ Co robimy w biurze
- przebudowy i rozbudowy dróg powiatowych i gminnych: projekty budowlane i wykonawcze, decyzje ZRID;
- **stała organizacja ruchu (SOR):** znaki, oznakowanie poziome, przejścia dla pieszych, opinie i zatwierdzenia;
- kosztorysy i przedmiary, specyfikacje techniczne (STWiORB);
- koordynacja branż: kanalizacja deszczowa, oświetlenie, teletechnika, sieci;
- uzgodnienia z gestorami sieci, pisma do urzędów, wydania dokumentacji na płytach.

Dla zarządów dróg powiatowych, gmin i inwestorów prywatnych: kilkadziesiąt tematów rocznie, w dwie osoby.

#### 🤖 Jak to łączymy z AI
- **Pamięć biura (MEMO):** kilka tysięcy notatek o projektach, decyzjach i wzorcach. Zanim AI o coś zapyta, najpierw szuka odpowiedzi tutaj.
- **Flota okien Claude Code:** „master” rozdaje robotę oknom projektowym i koderom w tle. Każda zmiana na żywo przechodzi najpierw przez agenta-adwersarza, którego zadaniem jest ją obalić.
- **Skany → OCR na GPU →** dokument sam trafia do właściwego projektu i do rejestru korespondencji.
- **Opisy techniczne i pisma** z wzorców biura (DOCX/PDF), a pod pisma do wysyłki helper z podpisem kwalifikowanym.
- **CAD (GstarCAD + AutoLISP):** narzędzia rysunkowe testowane w ukrytych instancjach, żeby nie przeszkadzać człowiekowi przy pracy.
- **Czat z zespołem**, w którym siedzi AI danego projektu i robi drobne poprawki na bieżąco.
- **Tańsze modele (Gemini Flash / Gemma)** przez własny router do masowej roboty. Opus i Sonnet zostają do myślenia.
- Wszystko **lokalnie i prywatnie**: sqlite, własny sejf na sekrety, kosz z cofaniem. Repo tylko prywatne.

#### 📱 Aplikacje web (zrobione z AI, telefon najpierw)
- **[Terapia, panel grupy wsparcia](https://consis-redroad.github.io/terapia/)**: kalendarz zajęć, prace domowe, czat jak w WhatsApp, materiały. Tu demo bez prawdziwych danych, a wersja dla grupy działa za logowaniem.
- **[Dzienniczek samoobserwacji](https://consis-redroad.github.io/dzienniczek/)**: prywatny dziennik emocji i myśli z logowaniem Google, który można zainstalować na telefonie.

#### 🧰 Na co dzień
`Claude Code` · `Python` · `MCP` · `GstarCAD / AutoLISP` · `sqlite` · `LiteLLM` · `Gemini` · `Tailwind / shadcn` · `PWA`

#### 📈 Liczby (10.2026)
~6,4 tys. commitów w workspace · ~6 tys. w pamięci MEMO · ~1 tys. w serwerach MCP · 37 person agentów · 30+ serwerów MCP

> Zasada, której się trzymam: powtarzający się błąd AI ma blokować hook, a nie kolejna linijka w prompcie.
