# do-call-with-par-r-util
do.call.with.par.R is a util function for R statistics

This was first published at code.google.com repository, and moved here, github.com.

do.call.with.par
http://code.google.com/p/cowares-excel-hello/source/browse/trunk/util_r/

Copyright (C) 2013 Tomizono
Fortitudinous, Free, Fair, http://cowares.nobody.jp
                           http://paidforeveryone.wordpress.com/

extract graphic parameters from dots argument
and call some graphical functions

 do.call.with.par('plot.default', list(...), 
                  xlim=lim[,1], ylim=lim[,2], 
                  x=NA, xlab='', ylab='', xaxt=axt[1], yaxt=axt[2])
 do.call.with.par('text', list(...), dots.win=T,
                  x=pt[1,1], y=pt[3,2], col=col.label,
                  labels=text)
