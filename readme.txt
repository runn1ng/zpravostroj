ummm... hello

this is a school project called Zpravostroj (meaning "news machine", maybe), that downloads stuff from major czech news sources, puts it in a BIIIIG database and then tries to somehow analyse it.

it heavily uses TectoMT - a "highly modular NLP (Natural Language Processing) software system implemented in Perl programming language under Linux." (from their site, http://ufal.mff.cuni.cz/tectomt/)

I guess it's all in GNU GPL v2, because it uses some chunks of GPL code now and then
[if it were my choice, I would use BSD, but what are you gonna do]

right now, it doesn't really work and it probably won't for a couple of weeks. but if you really want to use it, install TectoMT, put Zpravostroj/Modules into PERL5LIB and PERLLIB somehow, set some of the configure.yaml stuff like RSS and database, and ... do whatever you like, if you are lucky enough to figure out how to run it. 

AND. right now, the needed directiories are written as absolute paths in configure.yaml, and it's a file that gets updated TOGETHER with this git. so, it's not really for public use as a stand-alone product and it will probably never be.

thats all for now I guess


!!!!!!!!!!
one important thing
saving of themes is based on the assumpsion that you have filenames set as unicode
=
the program creates filenames WITH DIACRITICS.

If you don't like it, don't use it.... which you probably won't
