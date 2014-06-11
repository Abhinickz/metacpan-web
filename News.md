Title: Suggestion on incorrect number of colons
------------------------------
Date: 2014-06-09T08:15:00

Perl module name should contain only 2 colons, some common mistakes are we underuse or overuse it. Now, suggestion on no result page available when search with missing colon such as [Test:More](https://metacpan.org/search?q=Test%3AMore) or too much colons like [DBIx:::Class::::ResultSet](https://metacpan.org/search?q=DBIx%3A%3A%3AClass%3A%3A%3A%3AResultSet).
 
Title: Redirect to the module on 1 search result
------------------------------
Date: 2014-06-09T08:15:00

If there's only 1 result return from a search, it will take you that module automatically. For example search for ['ctx_request'](https://metacpan.org/search?q=ctx_request), you'll see Catalyst::Test module page instead of result page.

Title: Table sorting is now persistent
------------------------------
Date: 2014-05-19T10:50:12

When you change the sorting of a table it will be saved in your
browser's localStorage so that the next time you view that particular table
it will remember your last preference.  This is saved on a per table basis
(for example, author releases, author favorites, and reverse dependency releases).
No need to set it every time when accessing that page in the same browser.

Title: Details of (++)plussers displayed
------------------------------
Date: 2014-05-12T18:40:17

To get a better insight of which Pause users have ++ed a particular distribution, a list of their gravatar images is displayed.
Also, the count of non-Pause plussers makes it easier to know how many users have liked the module.

Hence, it gives us a perception of the people who recommend the module.


Title: Dependency Graphs are Here
------------------------------
Date: 2014-05-13T20:50:10

Jeffrey Thalhammer took the time this week to contribute dependency graphs to
MetaCPAN.  The graphs are hosted by [Stratopan](http://stratopan.com) and they
can be found on module and release pages under the "Reverse Dependencies" link.

Thanks very much to [THALJEF](https://metacpan.org/author/THALJEF) for
implementing this new feature.


Title: News feed of MetaCPAN created
------------------------------
Date: 2014-04-15T21:10:10


In this news feed you can follow the development of the MetaCPAN site.
There is also an [Atom feed](/feed/news).

If you are interested in how the news feed itself was implemented, check out
the article [Adding a News Feed to
MetaCPAN](http://perlmaven.com/adding-news-feed-to-metacpan)

