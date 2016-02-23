# factsandfictions-logo
The logos for facts&amp;fictions

## Installation

$ component install FctsFxns/fctsfxns-logo

## API

<* class="logo" data-logo="factsandfictions" data-color="purple|white|black|blue">
  <*></*>
</*>

<* class="logo" data-logo="factsandfictions-square" data-color="purple|white|black|blue">
  <*></*>
</*>

## CSS Classes for the logo

### logo version

- wrapper: svg#fctsfxns-logo-wrapper
	- logo: g#fctsfxns-logo g.logo
	  - letters: path.fctsfxns-logo-letter
	    - facts: path.fctsfxns-logo-letter-fa
	    - &: path.fctsfxns-logo-letter-and
	    - fictions: path.fctsfxns-logo-letter-fi

**scss**

	#fctsfxns-logo-wrapper {
		#fctsfxns-logo {
		  .fctsfxns-logo-letter {
			  fill: #593F7F; 
			  &.fctsfxns-logo-letter-fa {}
			  &.fctsfxns-logo-letter-and {}
			  &.fctsfxns-logo-letter-fi {}
			}
		}
	}


- Demo logo: http://codepen.io/dcanetma/pen/mVENPr

### square logo version

- wrapper: svg#fctsfxns-logo-sq-wrapper
	- fondo: rect#fctsfxns-sq-logo-bg
	- lines: polygon.fctsfxns-sq-line 
	  - line first: polygon.fctsfxns-sq-line-first
	  - line first: polygon.fctsfxns-sq-line-last
	- logo: path.fctsfxns-sq-logo
	  - square f: path.fctsfxns-sq-logo-square 
	  - root f:   path.fctsfxns-sq-logo-root

**scss**

	#fctsfxns-logo-sq-wrapper {
	  #fctsfxns-sq-logo-bg {
			fill: #0274d8; 
	  }
	  .fctsfxns-sq-line {
		  fill: #ffffff; 	    
	      &.fctsfxns-sq-line-first {}
	      &.fctsfxns-sq-line-last {}
	  }
	  .fctsfxns-sq-logo {
	    fill: #ffffff; 
		&.fctsfxns-sq-logo-root {}
		&.fctsfxns-sq-logo-square {}
	  }
	}



- Demo square logo: http://codepen.io/dcanetma/pen/PZGYBV