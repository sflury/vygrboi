# vygrboi

`vygrboi` is a custom color palette for data science visualization. I developed this scheme in an effort to create more aesthetic and vivid figures than facilitated by matplotlib defaults. Inspiration for the inital scheme came from discussions with my fiancee and a read through the [xkcd color survey](https://xkcd.com/color/rgb/). A critical element to this color scheme is testing for color-blind accessibility. I ran the scheme through [coolers.co](https://coolors.co/) and did some serious tweaking to make the scheme not only color-blind accessible but also black-white printer friendly. I generated the visual below using coolers and have included some examples where I have used `vygrboi` in my own work.

## The Palette

<img width="512" alt="image" src="https://github.com/sflury/vygrboi/assets/42982705/3f8618ac-7448-4002-b9f4-913a9264a619">

## Examples

Cartoon model of Lyman continuum escape in a patchy interstellar medium (Flury+ 2024 in prep)

<img width="512" alt="image" src="https://github.com/sflury/vygrboi/assets/42982705/77a65155-f804-488d-95b3-47bacbea6bd9">

## Naming `vygrboi`

I am an avid Star Trek fan and grew up on the original series and movies. The name `vygrboi` is inspired in part by the entity known as V'ger from the first Star Trek movie and played a role in dictating the order of my `matplotlib` color cycler.

## Included in this Repository

In addition to listing my hex codes, I have also provided my customized `matplotlib.rc` file. This file includes the `vygrboi` color cycler and improvements to visualization such as larger tick and axis labels, interior tick marks made longer, and cleaner subplot margins.
