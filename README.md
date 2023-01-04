# nedbor
Weather forecast using Met's API

## Requirements
* curl
* jq
### Optional
For block graphics (Radar)

* mpv
For proper graphics (Radar, weather icons)
* kitty 


![nedbor1](https://user-images.githubusercontent.com/35223282/196426486-1015e7e6-8792-496b-8839-404fa05b6158.gif) <br>

![nedbor2](https://user-images.githubusercontent.com/35223282/196426502-6d95c94d-d86c-4d47-9fd1-200539dac35a.gif)


## Usage

Nedbor manual
 Bilder og animasjoner støttes kun i Kitty Terminal<br>
 <code>-r Radarbilde over lokasjon<br>
 -l Spesifiser By (feks: Paris)<br></code>
 Uten options, kjøres bare: <code> -l Oslo </code>

### Example 1
<code> nedbor </code>
#### Output 
<code> It is 8.5° and rain outside in Oslo </code>

### Example 2
<code> nedbor -l Paris </code>
#### Output
<code> It is 16.6° and lightrain outside in Paris </code>
