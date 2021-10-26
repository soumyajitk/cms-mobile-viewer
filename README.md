# cms-mobile-viewer
Changes

   - Any word in the content starts with "<<" and ends with ">>" will have a meaning in Cosmic universal glossary. The starts and end signs have been removed an     changed word style to bold(<< Hello >> --> **Hello**) and meaning of that word will popup on mouse hover on that word.
   - Added a button called collection, so any word starts with "{{" and ends with "}}" will get replaced by a collections variable value. If collections variable      matches with that word.  


format will end up looking like
-    **https//whateverUrl** *?slug=foo-bar&collection=collection-slug*

    (where the bold is the url fragment and the italics is the query string)
