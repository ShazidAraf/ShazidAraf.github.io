# ShazidAraf.github.io

Personal website of Md Shazid Islam: https://shazidaraf.github.io/

## Files

- `index.html`: the whole site (one page, no build step).
- `Md_Shazid_Islam_Resume.pdf`: resume linked from the site. `resume.pdf` is a copy for old links.
- `assets/profile.jpg`: cropped profile photo used on the page. `profile_pic.jpg` is the original.
- `assets/media/`: project demos.

## Adding a project GIF

Drop a file with the matching name into `assets/media/`. The placeholder disappears on its own.

| Project | File |
|---|---|
| LINGUAL | `lingual.gif` |
| Uncertainty for 3D VLMs | `uncertainty-3d-vlm.gif` |
| Radiology report generation | `radiology-report.gif` |
| ODES | `odes.gif` |
| DEGAST3D | `degast3d.gif` |
| Synthesis of Style-Specific Dance (small card) | `dance.gif` |

Keep GIFs under about 5 MB. For an MP4, replace the `<img>` in that project's `<figure class="media">` with
`<video src="assets/media/name.mp4" autoplay muted loop playsinline></video>`.

## Photography

- `photos/index.html`: the full photo page (all photos, click to open full size).
- `assets/photos/full/`: large copies (about 1800 px). `assets/photos/thumb/`: grid copies (about 720 px).
- The home page shows 8 of them in the Beyond research section.

To add a photo, put both sizes in those folders with the same file name, then copy one `<figure class="pcard">` block in `photos/index.html` and change the file name and caption.
