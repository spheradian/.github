<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/spheradian/spheradian/main/docs/brand/spheradian-logo-transparent.svg">
    <img src="https://raw.githubusercontent.com/spheradian/spheradian/main/docs/brand/spheradian-logo-light.svg" alt="Spheradian logo: a wireframe sphere with a curved window whose solid angle is drawn back to the viewer at its center" width="140">
  </picture>
</p>

<h3 align="center">A spherical 3D desktop, built around trust domains.</h3>

Spheradian places you at the center of a 360° sphere. Windows are curved surfaces at their own depth, and every window carries a compositor-drawn border that shows which trust domain it belongs to. It is written in safe Rust, rendered with `wgpu`, and aimed at Linux and BSD.

The name joins *sphere* with *radian*, after the steradian: the unit of solid angle, which measures how much of the sphere each window takes up.

## Projects

| Repository | What it is |
| --- | --- |
| [**spheradian**](https://github.com/spheradian/spheradian) | The desktop itself: sphere, camera, curved windows, Mini-Globe overview, and the trust-domain security engine. |
| [**files**](https://github.com/spheradian/files) | A spatial file manager concept: folders as a city, plus a 3D sector map. [Try the browser demo.](https://spheradian.github.io/files/) |

## Status

Spheradian is an **early prototype (v0.0.1)**. It runs as a regular window on your existing desktop and is not yet a security boundary. The path to a real Wayland compositor session is on the [roadmap](https://github.com/spheradian/spheradian#roadmap).

## Get involved

- **Website and demos:** https://spheradian.github.io/spheradian/
- **Contributing:** start with the [contributing guide](https://github.com/spheradian/spheradian/blob/main/CONTRIBUTING.md). Platform reports, especially from BSD, non-Mesa drivers, and HiDPI setups, are very welcome.
- **Security:** please report vulnerabilities privately as described in the [security policy](https://github.com/spheradian/spheradian/blob/main/SECURITY.md), never in public issues.

All projects are released under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), except [Spheradian Files](https://github.com/spheradian/files), which is still under the MIT License until it is relicensed. The Spheradian and SpheradianOS names and logos are not covered by the code licence.
