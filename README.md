# Aruanda playtest

Public playtest builds of **Aruanda** (a working name), a co-op survival game drawn from Brazilian folklore. This repository holds
only builds and notes, no source.

"Aruanda" is a sacred place in Umbanda. We use the name with respect while the title is open.

## Get the build

Open **Releases** on this repo and download the zip of the newest pre-release. Unzip it and double-click `Aruanda.exe`.
Windows only. The exe is unsigned, so Windows SmartScreen shows a warning first: click "More info", then "Run anyway".

- **The co-op playtest** (beta-2): one to four Steam friends on one island. Steam must be running; Steam shows the game
  as "Spacewar". The zip's `README.txt` says who presses Join and who presses Host.
- **A solo playtest** shows only Play, a language button and Quit.

GitHub's "Source code" archives on a release hold only this README. No game source ships. A .NET game's code can be read
back from its files, as with any such game.

## What to do

The release notes list what to try (about 15 minutes), the controls and the known gaps. Then tell us how it felt.

## Report a problem

Open an **Issue** on this repo and attach:

- `%APPDATA%\Godot\app_userdata\Aruanda\logs\godot.log`
- in co-op, `coop-log.txt` from beside `Aruanda.exe`, from every PC in the game
- for a solo build, `frames.txt`, made by double-clicking `bench.bat` in the zip (10 to 15 minutes; leave the PC alone),
  with your GPU's name

## Privacy

A solo build sends nothing anywhere; a co-op build talks only to Steam and to the players in your game, and its
`coop-log.txt` holds their Steam names. `godot.log` can carry your Windows user name in its paths. `frames.txt` from `bench.bat`
records the date, your CPU, RAM, GPU and driver, and screen size, and Godot's own output follows, and it can carry
file paths too. Read both files before you send them.

## Licences

Godot Engine (MIT), the .NET runtime 8.0.33 (MIT), Facepunch.Steamworks (MIT), in co-op builds Valve's `steam_api64.dll`
(Steamworks SDK Access Agreement), and the placeholder sounds by Kenney (CC0). The full texts are in
the zip: `LICENSES.txt`, `godot-COPYRIGHT.txt` and `THIRD-PARTY-NOTICES.TXT`. The models are built by AI agents from code;
the folklore creatures are original.

---

## Português

Versões de teste públicas de **Aruanda** (nome provisório), um jogo cooperativo de sobrevivência inspirado no folclore
brasileiro. Este repositório guarda só as versões e as notas, sem código-fonte.

"Aruanda" é um lugar sagrado na Umbanda. Usamos o nome com respeito enquanto o título não for definido.

**Baixar:** abra **Releases** neste repositório e baixe o zip da versão mais nova (marcada como "Pre-release"). Descompacte e dê dois cliques em
`Aruanda.exe`. Só Windows e só um jogador, por enquanto. A tela inicial tem Jogar, um botão de idioma e Sair. O exe não é assinado, então o SmartScreen mostra um aviso antes: clique
em "Mais informações" e depois em "Executar assim mesmo".

Os arquivos "Source code" de uma versão contêm só este README. O código do jogo não é distribuído; o código de um jogo em
.NET pode ser lido a partir dos arquivos dele, como em qualquer jogo assim.

**Relatar um problema:** abra uma **Issue** (um chamado) aqui e anexe `%APPDATA%\Godot\app_userdata\Aruanda\logs\godot.log`
e o `frames.txt` gerado pelo `bench.bat` (de 10 a 15 minutos; não mexa no PC), com o nome da sua placa de vídeo.

**O que fazer:** as notas da versão listam o que experimentar (uns 15 minutos), os controles e as limitações conhecidas. Depois, conte para a gente o que achou.

**Privacidade:** a versão não envia nada. O `godot.log` pode conter seu nome de usuário do Windows nos caminhos. O
`frames.txt` do `bench.bat` registra a data, a CPU, a RAM, a placa de vídeo e o driver, e a resolução da tela; a saída do
próprio Godot vem depois e também pode conter caminhos de arquivos. Leia os dois antes de enviar.

**Licenças:** Godot Engine (MIT), o runtime do .NET 8.0.33 (MIT), Facepunch.Steamworks (MIT) e os sons provisórios do Kenney (CC0); os textos
completos estão no zip. Os modelos são feitos por agentes de IA a partir de código; as criaturas do folclore são originais.
