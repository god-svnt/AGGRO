




# Talfish

Talfish (AGGRO, as I've named it) is just a fork of [Stockfish][website-link] but made to play aggressive by adding an aggression value. Surprisingly works.

> **This is a modified version of Stockfish and is not the official Stockfish engine.**
> It is not affiliated with or endorsed by the Stockfish developers. The original
> project lives at <https://github.com/official-stockfish/Stockfish>.

## License

Talfish is a derivative work of Stockfish and, like Stockfish, is free software
distributed under the **GNU General Public License, version 3 or (at your option)
any later version**.

- The full license text is in [`Copying.txt`](Copying.txt) in this repository
  (official copy: [Stockfish `Copying.txt`][license-link]).
- GPLv3 on gnu.org: <https://www.gnu.org/licenses/gpl-3.0.html>
- Every source file keeps its original Stockfish copyright and license header.
  Please do not remove them.

In short, you are free to use, modify and redistribute this engine, provided that:

1. you keep the license and copyright notices intact,
2. you mark your changes as modified versions,
3. you license the whole work under the GPL as well, and
4. you make the corresponding source code available to anyone you give binaries to.

This summary is not legal advice. The license text in `Copying.txt` is what applies.

## Credits

Talfish exists thanks to the work of the Stockfish project and everyone who has
contributed to it.

- **Stockfish authors:** see the [`AUTHORS`](AUTHORS) file in this repository
  (official list: [Stockfish AUTHORS][authors-link]).
- **Founders:** Tord Romstad, Marco Costalba, Joona Kiiski and Gary Linscott.
- **NNUE:** Yu Nasu, Motohiro Isozaki and Hisayori Noda, authors and inventors of
  NNUE and its Stockfish port.
- **Stockfish website:** <https://stockfishchess.org>
- **Source code:** [official-stockfish/Stockfish][src-link]
- **Testing framework:** [Fishtest][fishtest-link], which the Stockfish project
  relies on for development.
- **Glaurung:** Stockfish is derived from Glaurung 2.1 by Tord Romstad.

Stockfish's neural network training data is derived in part from Leela Chess Zero
data ([lc0 training data][lc0-data-link]), used under the
[ODbL][odbl-link]. See the [official README][readme-link] for details on that.

## Modifications

Compared to upstream Stockfish, this fork adds an aggression value to the search to
make the engine play more aggressively. All other code is Stockfish's. For
everything else (compiling, UCI commands, usage), see the
[Stockfish wiki][wiki-link].

[authors-link]:       https://github.com/official-stockfish/Stockfish/blob/master/AUTHORS
[build-link]:         https://github.com/official-stockfish/Stockfish/actions/workflows/stockfish.yml
[commits-link]:       https://github.com/official-stockfish/Stockfish/commits/master
[discord-link]:       https://discord.gg/GWDRS3kU6R
[issue-link]:         https://github.com/official-stockfish/Stockfish/issues/new?assignees=&labels=&template=BUG-REPORT.yml
[discussions-link]:   https://github.com/official-stockfish/Stockfish/discussions/new
[fishtest-link]:      https://tests.stockfishchess.org/tests
[guideline-link]:     https://github.com/official-stockfish/fishtest/wiki/Creating-my-first-test
[license-link]:       https://github.com/official-stockfish/Stockfish/blob/master/Copying.txt
[programming-link]:   https://www.chessprogramming.org/Main_Page
[programmingsf-link]: https://www.chessprogramming.org/Stockfish
[readme-link]:        https://github.com/official-stockfish/Stockfish/blob/master/README.md
[release-link]:       https://github.com/official-stockfish/Stockfish/releases/latest
[src-link]:           https://github.com/official-stockfish/Stockfish/tree/master/src
[stockfish128-logo]:  https://stockfishchess.org/images/logo/icon_128x128.png
[uci-link]:           https://backscattering.de/chess/uci/
[website-link]:       https://stockfishchess.org
[website-blog-link]:  https://stockfishchess.org/blog/
[wiki-link]:          https://github.com/official-stockfish/Stockfish/wiki
[wiki-compile-link]:  https://github.com/official-stockfish/Stockfish/wiki/Compiling-from-source
[wiki-uci-link]:      https://github.com/official-stockfish/Stockfish/wiki/UCI-&-Commands
[wiki-usage-link]:    https://github.com/official-stockfish/Stockfish/wiki/Download-and-usage
[worker-link]:        https://github.com/official-stockfish/fishtest/wiki/Running-the-worker
[lc0-data-link]:      https://storage.lczero.org/files/training_data
[odbl-link]:          https://opendatacommons.org/licenses/odbl/odbl-10.txt

[build-badge]:        https://img.shields.io/github/actions/workflow/status/official-stockfish/Stockfish/stockfish.yml?branch=master&style=for-the-badge&label=stockfish&logo=github
[commits-badge]:      https://img.shields.io/github/commits-since/official-stockfish/Stockfish/latest?style=for-the-badge
[discord-badge]:      https://img.shields.io/discord/435943710472011776?style=for-the-badge&label=discord&logo=Discord
[fishtest-badge]:     https://img.shields.io/website?style=for-the-badge&down_color=red&down_message=Offline&label=Fishtest&up_color=success&up_message=Online&url=https%3A%2F%2Ftests.stockfishchess.org%2Ftests%2Ffinished
[license-badge]:      https://img.shields.io/github/license/official-stockfish/Stockfish?style=for-the-badge&label=license&color=success
[release-badge]:      https://img.shields.io/github/v/release/official-stockfish/Stockfish?style=for-the-badge&label=official%20release
[website-badge]:      https://img.shields.io/website?style=for-the-badge&down_color=red&down_message=Offline&label=website&up_color=success&up_message=Online&url=https%3A%2F%2Fstockfishchess.org
