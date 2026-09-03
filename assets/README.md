# assets

SVG, all of it, and nothing here is fetched from anywhere. `rail.svg` is hand-written; the
eight tiles in `map/` are written by a build script that lives outside the published repo, so
editing one of those files directly is pointless — the next build overwrites it.

`rail.svg` — the gradient bar at the top of every page except the root.

`map/` — the eight tiles the root page is built from. They sit flush in two rows and most of
them are their own link, which is the only way GitHub allows a picture to have more than one click
target: links inside an SVG are stripped, and a table would put borders between the cells.

They have no background of their own. The page shows through, so the seam where two tiles meet and
the margin between the two rows stay invisible whatever theme the reader uses. Everything drawn is
chosen to read on a white page and on a near-black one.

The connector traces run across the tile edges, so changing one tile usually means changing its
neighbour.

The project cards carry the Claude and AWS marks. They are base64-embedded inside the tiles
rather than sitting here as image files, because an SVG used as an `<img>` may not load an external
image and nothing here points outside the repository. The reversed version is used, so the AWS wordmark
stays readable on the dark card. They name the course and the certification being
worked through; they do not claim any endorsement, and neither company has anything to do with this
repository.

A running project's tile carries its lesson count, which moves when the course does — which is
why these are generated rather than typed. A finished one drops the number and says `FINISHED`
with a green tick after it, so nothing on the map goes stale any more.

Finished also means still: the trace keeps its own colour but the electrons come off it. The tick
is the only green anywhere in the map and it is always inside a card, so the card's colour still
means where the project sits on the rail rather than how far along it is.

All of it lives in the repo on purpose. A badge service or an image host would mean a third party
gets a request, and a log entry, every time someone opens one of these pages. This way the page
asks nothing of anyone.

Nothing else belongs in this folder.
