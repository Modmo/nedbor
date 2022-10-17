# nedbor
Weather forecast using Met's API

## Requirements
* curl
* jq
### Optional
For graphics (Radar, weather icons)
* kitty

## Usage

Nedbor manual
 Bilder og animasjoner støttes kun i Kitty Terminal
 -r Radarbilde over lokasjon
 -l Spesifiser By (feks: Paris)
 Uten options, kjøres bare: -l Oslo

### Example 1
<code> nedbor </code>
#### Output 
<code> It is 8.5° and rain outside in Oslo </code>

### Example 2
<code> nedbor -l Paris </code>
#### Output
<code> It is 16.6° and lightrain outside in Paris </code>
