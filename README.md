# Magic Academy — OOC Image Library

Official asset repository for **Magic Academy / Veylspire Academy of Arcane Arts**.

## Public image hosting

This repository is published through GitHub Pages at:

https://gilbertjulio14-ux.github.io/academy/

**OOC reaction image base URL**

```text
https://gilbertjulio14-ux.github.io/academy/images/reactions/
```

Images use a **two-letter filename**: `[character][emotion].png`, with no setting code.

### Character codes

```text
E=Elara Wren            M=Mirelle Tidehart
C=Cassia Vaelmont       T=Talia Sparks
I=Ivy Bramble           S=Seraphine Thornwick
N=Nia Gale              O=Ophelia Larkspur
L=Selene Maris          R=Rhea Volkar
D=Dahlia Greymark       J=Juniper Quill
B=Isolde Briarstone     A=Aurelia Finch
F=Maevra Fen            H=Helena Ashbourne
Q=Corinne Vesper        Y=Ysadora Hollow
P=Alaric Veyl           W=Lady Morwen Vaelmont
X=Nyx Caligo            V=Severin Noct
```

### Emotion codes

```text
N = Neutral       H = Happy       D = Sad
A = Angry         S = Shy         K = Kiss
C = Squeezing cheek
```

Examples (available **only after the corresponding files are uploaded**):
- `images/reactions/EN.png` — Elara, neutral
- `images/reactions/CA.png` — Cassia, angry
- `images/reactions/XK.png` — Nyx, kiss

OOC Markdown example:

```markdown
![](https://gilbertjulio14-ux.github.io/academy/images/reactions/CA.png)
```

## Folder structure

- `images/reactions/` — Character expression sprites used dynamically by OOC.
- `images/characters/` — Character portraits and other character art.
- `images/worlds/` — Backgrounds, locations, environments and map artwork.
- `index.html` — Lightweight Pages landing page. Can be replaced with a full Magic Academy website.

**Important:** Filenames are case-sensitive. Only reference files that actually exist; uploading the images is a separate step.

## Deployment

GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/(root)`.

Public GitHub Pages is suitable for a small image library, but it is subject to GitHub usage limits and is not a dedicated image CDN.
