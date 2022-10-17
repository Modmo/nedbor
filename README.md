# nedbor
Weather forecast using Met's API

## Requirements
* curl
* jq
### Optional
For graphics (Radar, weather icons)
* kitty 


![nedbor](https://user-images.githubusercontent.com/35223282/196269220-510fd607-590d-4065-957c-b442ab268d38.gif)


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
