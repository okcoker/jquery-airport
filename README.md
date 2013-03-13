jQuery Airport
==============

Airport is a rather simple text effect plugin for Jquery. It emulates the style of those flickering information boards you sometimes find on airports and train stations. [Demo](http://seancoker.com/projects/airport)

How to use Airport
==================
Airtport is very easy to use. Create an element, give it an ID and throw airport on it. The values, moscow, berlin and stockholm, are the words it will flick through.

`$(  element  ).airport([ 'moscow', 'berlin', 'stockholm' ]);`

Options
=======
`transition_speed` - {number} Time in ms before switching to the next word

Default value - 1000,


`loop` - {boolean} Choose whether to stop at the end of your values or keep looping through

Default value - true,


`fill_space` {boolean} - Puts spaces (nbsp) after shorter words to fill in space of your longest word

Default value - false


`colors` {String} - List of comma separated colors to randomly color your values i.e. '#b5c523,#E7860E'

Default value - null


Special Thanks
==============

Original work by [Jan Järfalk](http://unwrongest.com/projects/airport/)