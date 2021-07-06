# Markazi Text Family
By Borna Izadpanah, Florian Runge and Fiona Ross

This typeface design was inspired by Tim Holloway’s Markazi typeface, with his encouragement, and initiated by Gerry Leonidas as a joint University of Reading and Google project. The Arabic typeface, designed by Borna Izadpanah and design directed by Fiona Ross, is a text typeface with moderate contrast. It takes its cues from the award-winning Markazi typeface, affording a contemporary and highly readable typeface. The complementary Latin typeface was designed by Florian Runge. It keeps in spirit with its Arabic counterpart, echoing key design characteristics while being rooted in established Latin traditions. It is an open and clear design with a compact stance and an evenly flowing rhythm. Both Arabic and Latin are available in four weights with extended language support suited for print and screen.

![Specimen](https://github.com/BornaIz/markazitext/blob/master/Specimen/Markazi%20Text_1.PNG)

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you particularly want to build fonts manually on your own computer, you will need to install the [`yq` utility](https://github.com/mikefarah/yq). On OS X with Homebrew, type `brew install yq`; on Linux, try `snap install yq`; if all else fails, try the instructions on the linked page.

Then:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at
http://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.