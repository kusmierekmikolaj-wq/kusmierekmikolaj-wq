### Cześć, jestem Mikołaj 👋

Buduję narzędzia, w których AI robi prawdziwą robotę, i sprawdzam je pomiarami, a nie obietnicami.
Interesuje mnie kodowanie z modelami językowymi, robotyka i druk 3D.

*I build tools where AI does real work, and I check them with measurements, not promises.
Interests: coding with LLMs, robotics, 3D printing. Based in Poland.*

---

#### <img src="https://raw.githubusercontent.com/kusmierekmikolaj-wq/reel-intel/main/assets/logo.svg" width="22" height="22" alt=""> [reel-intel](https://github.com/kusmierekmikolaj-wq/reel-intel): dlaczego jedne krótkie filmy wybuchają, a inne nie

Z linków albo całego profilu (Instagram, TikTok, YouTube, X, Facebook) robi dosłowny tekst, pomiary obrazu i dźwięku
oraz uczciwą statystykę, wszystko lokalnie, bez kluczy API. Aplikacja w przeglądarce, wtyczka do Chrome, serwer MCP i wtyczka do Claude Code.
Na **262 filmach z 6 kont: żadna z 14 mierzonych cech nie powtarza się na dwóch kontach**, więc uniwersalnej recepty na viral nie ma.
Kontrola jakości ma autotest na 15 wstrzykniętych usterkach. Transkrypcja na prawdziwych wystąpieniach (angielskich i polskich): ok. 4% słów z ludzkich napisów nie zostaje odtworzone, 8% rozbieżności z napisami (górna granica); krótkich zaszumionych rolek jeszcze nie mierzyłem. Python, MIT.

*Turns links or a profile into verbatim text, picture and sound measurements and honest statistics, all on your computer.
On 262 videos from 6 accounts no format feature repeated across accounts. On four real talks (English and Polish) about 4% of the human subtitle words are missed, 8% disagreement as an upper bound; short noisy reels not yet measured.*

#### 🔥 [Iskra](https://github.com/kusmierekmikolaj-wq/iskra): kod z AI taniej, szybciej i bezpieczniej

Język i zestaw narzędzi do pisania kodu z modelami AI. `isk solve` zastępuje pętlę agenta jednym wywołaniem modelu,
a program sam wybiera kontekst, nakłada zmiany i uruchamia testy.
W benchmarku z preregistracją: **18/18 zadań za ok. 14% kosztu** domyślnego agenta i **ok. 2× szybciej**.
Checker bezpieczeństwa, testy oparte na właściwościach, serwer MCP. Node.js, MIT.

*A language and toolchain for AI-assisted coding. In a pre-registered benchmark `isk solve` solved 18/18 tasks
at ~14% of the default agent's cost, about 2× faster.*

#### AMSA — uwaga, pamięć i samomodelowanie u sztucznych agentów

Rozwijam **AMSA (Attention, Memory and Self-modeling in Agents)**: projekt badawczy oparty na publikacjach,
kodzie i powtarzalnych eksperymentach. Sprawdzam, kiedy modelowanie własnej uwagi pomaga agentowi
działać i co wnoszą pamięć oraz samomonitorowanie. Pierwszy etap to kontrolowana symulacja w Pythonie,
PyTorch i Gymnasium, z protokołami, testami i zapisem wyników. Sprawność agenta i subiektywne doświadczenie
to osobne pytania. Repozytorium pozostaje prywatne podczas porządkowania materiałów.

*AMSA — Attention, Memory and Self-modeling in Agents. A research project using scientific papers,
code and reproducible experiments to study attention control, memory and self-modeling in artificial agents.
The first stage uses controlled simulations in Python, PyTorch and Gymnasium. Functional performance
and subjective experience are separate research questions. The repository is private while the materials are being prepared.*


---

**Narzędzia / Tools:** JavaScript (Node.js) · Python · Claude API i Claude Code · MCP · faster-whisper · OpenCV · MuJoCo · Blender · FreeCAD · Git
