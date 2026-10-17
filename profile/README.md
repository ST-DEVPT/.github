<h1 align="center">ST-DEVPT</h1>

<p align="center">
  <b>Tools for the homelab, built to be left alone.</b><br>
  Small, careful software for the things that run in a rack and in the living room, made in Portugal.
</p>

---

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ST-DEVPT/rack-fan-control">Fan Control</a></h3>
      <p><b>Quiet rack servers, without cooking them.</b> Self-hosted fan control for Dell iDRAC, Supermicro
      and HPE iLO, with a smart mode that learns your server, fan calibration, and the BMC as the safety
      net whenever anything is unknown.</p>
      <p>
        <a href="https://github.com/ST-DEVPT/rack-fan-control/releases"><img alt="Release" src="https://img.shields.io/github/v/release/ST-DEVPT/rack-fan-control?color=e4501b"></a>
        <img alt="Docker" src="https://img.shields.io/badge/docker-amd64%20%7C%20arm64-2c6b8a">
        <img alt="Python, no dependencies" src="https://img.shields.io/badge/python-no%20dependencies-3b7a39">
      </p>
      <a href="https://github.com/ST-DEVPT/rack-fan-control"><img alt="Fan Control: three servers, each in its own fan mode" src="https://raw.githubusercontent.com/ST-DEVPT/rack-fan-control/main/docs/overview.jpg"></a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ST-DEVPT/Jellyflix">Jellyflix</a></h3>
      <p><b>Your Jellyfin on the living-room TV, the way Netflix feels.</b> An Android TV client written from
      scratch in Kotlin and Compose for TV: full-screen highlights, rows that grow with the focus, Top 10,
      4K HDR and Dolby Atmos, updates straight from GitHub.</p>
      <p>
        <a href="https://github.com/ST-DEVPT/Jellyflix/releases/latest"><img alt="Release" src="https://img.shields.io/github/v/release/ST-DEVPT/Jellyflix?label=release"></a>
        <img alt="Android TV 6.0+" src="https://img.shields.io/badge/Android%20TV-6.0%2B-3DDC84">
        <img alt="Jellyfin 12.0+" src="https://img.shields.io/badge/Jellyfin-12.0%2B-9457dc">
      </p>
      <a href="https://github.com/ST-DEVPT/Jellyflix"><img alt="Jellyflix: a full-screen highlight with the film's logo and the Continue watching row" src="https://github.com/ST-DEVPT/Jellyflix/releases/download/imagens/home.jpg"></a>
    </td>
  </tr>
</table>

### How we build

- **Safety before features.** When the software does not know, it hands control back to the thing that does.
- **No dependency we can avoid.** Plain Python, plain Kotlin, small images, nothing to keep patching.
- **Tested where it matters.** Unit and browser tests on every push, and fixes come with the test that failed before them.
- **Honest docs.** What works, what is experimental, and what no software can cover.

<p align="center"><sub>Found a bug or have hardware we have not seen? Open an issue on the project; the diagnostics file is all we need.</sub></p>
