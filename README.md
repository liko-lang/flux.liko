<p align="center">
  <img src="assets/camille.png" alt="Camille, the mascot of Liko" width="240">
</p>

<h1 align="center">flux.liko</h1>

**This repository contains the Flux module for the Liko data language. This module is officially maintained by the Liko team.**

It contains the complete set of Flux schema definitions.

---

## Installation

Initialize a local module with `liko init`, then add `flux.liko` as a dependency.

```bash
liko init
```
```bash
liko add flux
```

```bash
liko install
```

## Usage

The module can now be used from any directory within the current module.

```liko
#S: import "flux/source.toolkit.fluxcd.io/v1"

$: #S.GitRepository {
    metadata: {
        name: "a"
    } 
    spec: {
        url: "https://x"
        interval: "1m" 
    } 
}
```
