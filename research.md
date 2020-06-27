# web syndication research
## potential libraries
### generate
https://github.com/gorilla/feeds

### parse
https://github.com/mmcdole/gofeed
_didn't review yet_
- Full featured
- Uses goquery
https://github.com/ungerik/go-rss
- Very simple/barebones
- See note on user agents and reddit in rss.go - useful?
https://github.com/SlyMarbo/rss
- Old project
- Doesn't seem to support extensions
https://github.com/emmaly/go-pkg-rss
- Respects feed cache settings
- Old project
- Newer forks: mattn vs smarp
  - smarp: extensions in readAtom, more time formats


### full rss reader
https://github.com/miniflux/miniflux - postgres
- Self hosted browser based reader server
- See reader folder for all the parsing, etc
  - All dependencies seem to be internal or std lib (didn't look at all files)
- Does feed/content sanitizing with blacklist and whitelist.
https://github.com/spf13/dagobah - mongo
_didn't review yet_
- Old project
- uses go-pkg-rss
https://github.com/antavelos/terminews - TUI
- uses gofeed

## support for?
- JSON feed
  - https://jsonfeed.org/version/1
  - Adoption?
- Media RSS
  - https://en.wikipedia.org/wiki/Media_RSS
  - https://www.rssboard.org/media-rss (spec)


## further reading
http://www.tbray.org/ongoing/When/200x/2005/07/27/Atomic-RSS

### cool tangent
https://github.com/dertuxmalwieder/rssfs - mount an rss feed as a filesystem
- advice for making rss feeds atom compatible, not sure if widely followed
