# A Pulseing Circle CSS

## Usage
Add this CSS codes to your style:
```CSS
.pulse {
    content: '';
    display: inline-block;
    width: 10px;
    height: 10px;
    border-radius: 8px;
    animation: out 1s infinite ease-out;
    background: #00ff1a;
    margin: 0 9px -2px 1px;
    animation-name: out!important;
}

@keyframes out {
	0% {
		box-shadow: 0 0 #00ff1a;
	}
	100% {
		box-shadow: 0 0 0 10px rgba(0,121,173,0);
	}
}
```

Add `pulse` class to a `div` html tag.

```HTML
<div class="pulse"></div>
```
