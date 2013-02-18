MP3/Podcast version 0.06
========================

MP3::Podcast is a simple module, with accompanying scripts, to easily
create podcasts from a set of MP3s that have info included as ID3
tags. The current release can be downloaded from
http://search.cpan.org/~jmerelo/MP3-Podcast/ 
or using the usual
cpan MP3::Podcast
preceded by SUDO

INSTALLATION
=========

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

USE
===

Drop a few MP3s (or use those supplied in the directory t/music) and
use
bash% [whatever_dir]/examples/gen-podcast.pl directory_name
http://url.ba.se sub_dir

for instance, if you are right at the base dir
bash% examples/gen-podcast.pl t/music http://example.com . will
generate an RSS for the supplied (and CC-licensed) MP3s  supplied


DEPENDENCIES

This module requires these other modules and libraries:

  XML::RSS 1.05
  MP3::Info 1.13

COPYRIGHT AND LICENCE

Copyright (C) 2005-2013 Juan Julian Merelo Guervos

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself. 

