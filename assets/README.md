# assets

Hand-written SVG, all of it. Nothing here is generated and nothing is fetched from anywhere.

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

One tile carries a number: the lesson count in `tile-claude.svg`. It has to be edited by hand
when that count moves, and it is the only thing here that can go out of date.

All of it lives in the repo on purpose. A badge service or an image host would mean a third party
gets a request, and a log entry, every time someone opens one of these pages. This way the page
asks nothing of anyone.

Nothing else belongs in this folder.
