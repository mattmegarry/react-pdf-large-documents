Original code taken from https://github.com/wojtekmaj/react-pdf/issues/94#issuecomment-451736240

... with comment by @stefanbugge...

"
I've had success with rendering with react-pdf together with react-window. The implementation below is inspired by the react-virtualized implementation by @michaeldzjap above and the description provided by @nikonet. It's still a work in progress but so far it seems to perform well. Any suggestions to improve the implementation would be greatly appreciated.

One thing that concerns me, however:
By caching all page dimensions on document load I would assume that you would loose the ability of pdfjs to load pages in chunks with range requests. Any thoughts on this?
"
