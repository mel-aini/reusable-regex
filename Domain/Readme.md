this regex can be used to detect all the matching domain names in a string execluded from paths, queries and fragments

example:

input: <link href="https://plus.google.com/117150671992820587865">
result: https://plus.google.com/

input: src="http://www.widgets.outbrain.com/outbrain.js
result: http://widgets.outbrain.com