0.3.0 / 2013-10-18
==================
  * Changed ext grammar to parse id and direction as one (fixes writing bug)
  * Allow mid to be a string (fixes bug)
  * Add support for maxptime value
  * Add support for ice-options
  * Add support for grouping frameworks
  * Add support for msid-semantic
  * Add support for ssrc
  * Add support for rtcp-mux
  * Writer improvements: add support for session level push attributes

0.2.1 / 2013-07-31
==================
  * Support release thanks to @legastero, following was pulled from his fork:
  * Add support for rtcp-fb attributes.
  * Add support for header extension (extmap) attributes.
  * Add support for crypto attributes.
  * Add remote-candidates attribute support and parser.

0.2.0 / 2013-07-27
==================
  * parse most normal lines sensibly
  * factored out grammar properly
  * added a writer that uses common grammar
  * stop preprocessing parse object explicitly (so that parser ∘ writer == Id)
    these parser helpers are instead exposed (may in the future be extended)

0.1.0 / 2013-07-21
==================
  * rewrite parsing mechanism
  * parse origin lines more efficiently
  * parsing output now significantly different

0.0.2 / 2012-07-18
==================
  * ice properties parsed

0.0.1 / 2012-07-17
==================
  * Original release
