<!--
-----------------------------------------------
	inline-svg sprite
	- common used svg-stuff (feather-icons)
	- advantage of css-styling
	- https://github.com/jacobmischka/svelte-feather-icon
	- https://feathericons.com/
	- if requred we can split out app-controls to REPL only
-----------------------------------------------
-->

<svg style='display:none'>
	<symbol id='arrow-left' class='icon' viewBox='0 0 24 24'>
		<line x1='19' y1='12' x2='5' y2='12' />
		<polyline points='12 19 5 12 12 5' />
	</symbol>

	<symbol id='arrow-right' class='icon' viewBox='0 0 24 24'>
		<line x1='5' y1='12' x2='19' y2='12' />
		<polyline points='12 5 19 12 12 19' />
	</symbol>

	<symbol id='arrow-up' class='icon' viewBox='0 0 24 24'>
		<line x1='12' y1='19' x2='12' y2='5' />
		<polyline points='5 12 12 5 19 12' />
	</symbol>

	<symbol id='arrow-down' class='icon' viewBox='0 0 24 24'>
		<line x1='12' y1='5' x2='12' y2='19' />
		<polyline points='19 12 12 19 5 12' />
	</symbol>

	<symbol id='check' class='icon' viewBox='0 0 24 24'>
		<polyline points='20 6 9 17 4 12' />
	</symbol>

	<symbol id='close' class='icon' viewBox='0 0 24 24'>
		<line x1='18' y1='6' x2='6' y2='18' />
		<line x1='6' y1='6' x2='18' y2='18' />
	</symbol>

	<symbol id='download' class='icon' viewBox='0 0 24 24'>
		<path d='M21 15V19A2 2 0 0 1 19 21H5A2 2 0 0 1 3 19V15' />
		<polyline points='7 10 12 15 17 10' />
		<line x1='12' y1='15' x2='12' y2='3' />
	</symbol>

	<symbol id='edit' class='icon' viewBox='0 0 24 24'>
		<path d='M20 14.66V20a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h5.34' />
		<polygon points='18 2 22 6 12 16 8 16 8 12 18 2' />
	</symbol>

	<symbol id='github' class='icon' viewBox='0 0 24 24'>
		<path
			d='M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22' />
	</symbol>

	<symbol id='git-branch' class='icon' viewBox='0 0 24 24'>
		<line x1='6' y1='3' x2='6' y2='15' />
		<circle cx='18' cy='6' r='3' />
		<circle cx='6' cy='18' r='3' />
		<path d='M18 9a9 9 0 0 1-9 9' />
	</symbol>

	<symbol id='log-in' class='icon' viewBox='0 0 24 24'>
		<path d='M15 3H19A2 2 0 0 1 21 5V19A2 2 0 0 1 19 21H15' />
		<polyline points='10 17 15 12 10 7' />
		<line x1='15' y1='12' x2='3' y2='12' />
	</symbol>

	<symbol id='maximize' class='icon' viewBox='0 0 24 24'>
		<path d='M8 3H5a2 2 0 0 0-2 2v3m18 0V5a2 2 0 0 0-2-2h-3m0 18h3a2 2 0 0 0 2-2v-3M3 16v3a2 2 0 0 0 2 2h3' />
	</symbol>

	<symbol id='maximize-2' class='icon' viewBox='0 0 24 24'>
		<polyline points='15 3 21 3 21 9' />
		<polyline points='9 21 3 21 3 15' />
		<line x1='21' y1='3' x2='14' y2='10' />
		<line x1='3' y1='21' x2='10' y2='14' />
	</symbol>

	<symbol id='menu' class='icon' viewBox='0 0 24 24'>
		<line x1='3' y1='12' x2='21' y2='12' />
		<line x1='3' y1='6' x2='21' y2='6' />
		<line x1='3' y1='18' x2='21' y2='18' />
	</symbol>

	<symbol id='message-square' class='icon' viewBox='0 0 24 24'>
		<path d='M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z' />
	</symbol>

	<symbol id='minus' class='icon' viewBox='0 0 24 24'>
		<line x1='5' y1='12' x2='19' y2='12' />
	</symbol>

	<symbol id='plus' class='icon' viewBox='0 0 24 24'>
		<line x1='12' y1='5' x2='12' y2='19' />
		<line x1='5' y1='12' x2='19' y2='12' />
	</symbol>

	<symbol id='save' class='icon' viewBox='0 0 24 24'>
		<path d='M19 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11l5 5v11a2 2 0 0 1-2 2z' />
		<polyline points='17 21 17 13 7 13 7 21' />
		<polyline points='7 3 7 8 15 8' />
	</symbol>

	<symbol id="link" class="icon" viewBox="0 0 24 24">
		<path d="M9,7L6,7A2 2 0 0 0 6,17L9,17" />
		<path d="M15,7L18,7A2 2 0 0 1 18,17L15,17" />
		<path d="M7,12L17,12" />
	</symbol>

	<symbol id="chevron" class="icon" viewBox="0 0 24 24">
		<path d="M2,7 L12,17 L20,7" />
	</symbol>

	<symbol id="play" viewBox="0 0 24 24">
		<polygon points="5 3 19 12 5 21 5 3" />
	</symbol>

</svg>