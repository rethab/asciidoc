Tests with AsciiDoc
===================
:Author:    Reto
:Date:      2017-01-31


Intro
-----
Document was created by {Author}

TIP: Does this show pretty icons?

Source Code
~~~~~~~~~~~

.Brewery
[source,scala]
----
/** some comment */
trait Brewery {

  val grinder: Grider

  def brew(): Coffee = ???
  
}
----
