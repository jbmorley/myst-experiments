# Myst Experiments

This repository is a collection of ideas and experiments for a 2-bit port of Myst (perhaps to the Playdate). Right now it's a collection of scripts for extracting and converting the original assets to see how they work in 2-bit.

## Examples

It's not yet clear which dithering algorithm would work best–Atkinson looks great and has a real retro-Mac feel, but Floyd-Steinberg definitely captures more detail.

### Movies

<table>
  <tr>
    <th>Atkinson</th>
		<th>Floyd-Steinberg</th>
  </tr>
  <tr>
    <td>
      <img src="examples/movies/INTRO-atkinson.gif">
    </td>
    <td>
      <img src="examples/movies/INTRO-floydsteinberg.gif">
    </td>
  </tr>
  <tr>
    <td>
      <img src="examples/movies/INTRO2-atkinson.gif">
    </td>
    <td>
      <img src="examples/movies/INTRO2-floydsteinberg.gif">
    </td>
  </tr>
  <tr>
    <td>
      <img src="examples/movies/GEARS-atkinson.gif">
    </td>
    <td>
      <img src="examples/movies/GEARS-floydsteinberg.gif">
    </td>
  </tr>
</table>


### Frames

![Myst03](examples/frames/Myst03.jpg)

![Myst05](examples/frames/Myst05.jpg)

![Myst06](examples/frames/Myst06.jpg)