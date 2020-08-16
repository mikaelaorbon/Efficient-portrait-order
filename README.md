# Efficient-portrait-order

It is common at weddings and other large formal social gatherings to take group portraits of many different combinations of people; ex. the couple, the couple and their families, the couple and their parents, the couple and the wedding party, etc.

In general, it is desirable to take large group shots first, so that guests who aren't needed for further pictures may be dismissed to join the party.

This application finds the ordering of pictures that will allow the most people to be dismissed as early as possible. Specifically, it _minimizes_ the aggregate waiting time, i.e. the number of portraits that individuals must be present for, assuming that each person must be present for every portrait from the first one (regardless of whether it includes them) until the last one that includes them.

__Status 8/16/20:__ Algorithm has been devised, implemented in Python, and tested. Next steps are to rewrite it in JavaScript, then create a web app with UI.
