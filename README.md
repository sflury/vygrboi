# vygrboi

`vygrboi` is a custom color palette for data science visualization. I developed this scheme in an effort to create more aesthetic and vivid figures than facilitated by matplotlib defaults. Inspiration for the inital scheme came from discussions with my fiancee and a read through the [xkcd color survey](https://xkcd.com/color/rgb/). A critical element to this color palette is testing for color-blind accessibility. I ran the palette through [coolers.co](https://coolors.co/) and did some serious tweaking to make the palette not only color-blind accessible but also black-white printer friendly. I generated the visual below using coolers and have included some examples where I have used `vygrboi` in my own work.

## The Palette

<img width="512" alt="image" src="https://github.com/user-attachments/assets/2ce6e3ad-34cd-47e3-bad1-18c1d4ad1a59">

## Examples

Cartoon model of Lyman continuum escape in a patchy interstellar medium (Flury+ 2025a)

<img width="512" alt="image" src="https://github.com/sflury/vygrboi/assets/42982705/77a65155-f804-488d-95b3-47bacbea6bd9">

Contours of constant observed velocity (Flury 2025c) also known as isocontours or velocity surfaces

<img width="456" height="331" alt="image" src="https://github.com/user-attachments/assets/32707da7-35f7-46f6-a363-3e6f491d3b00" />


## Naming `vygrboi`

I am an avid Star Trek fan and grew up on the original series and movies. The name `vygrboi` is inspired in part by the V'ger entity (vividly colorful itself) from the first Star Trek movie and played a role in dictating the order of my `matplotlib` color cycler.

## Included in this Repository

In addition to listing my hex codes, I have also provided a customized `matplotlibrc` file named `matplotlibrc.vygrboi`. This file includes the `vygrboi` color cycler and improvements to visualization such as larger tick and axis labels, interior tick marks made longer, and cleaner subplot margins.
