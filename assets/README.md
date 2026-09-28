# assets

SVG, all of it, and nothing here is fetched from anywhere. Every file is written by a build
script that lives outside the published repo, so editing one of them directly is pointless —
the next build overwrites it.

`map/` — the skill tree on the root page, cut into tiles. GitHub strips links inside an SVG,
so the only way a picture gets more than one click target is a row of `<a><img></a>`. The tree
is drawn once and cut along the edges of its cards: a tile inside a card is that card's link,
every other tile is wrapped in `<a name>` so it links nowhere. Only the cards are clickable.
A new project is one more branch and one more card; the cutting follows by itself.

`headers/` — one picture at the top of every page below the root: the branch you followed on
the map, seen up close. A project on the right of the tree is reached from the upper left, one
on the left from the upper right, the pages under the roots from above. Flat on purpose: the
text under it is what the page is for.

`leaves/` — the marks in front of the section headings. Their order is their position along
the branch, from deep petrol to amber, with a grey one for the closing section.

The tree sits on its own night-green panel instead of the page background. GitHub's theme
switch is invisible to an image, so a picture cannot follow it; a panel of its own looks the
same to everyone. Anything outside the panel — the leaves — is a mid-tone that reads on a
white page and on a near-black one.

The project cards carry the Claude and AWS marks, base64-embedded because an SVG used as an
`<img>` may not load an external image. They name the course and the certification being worked
through; they do not claim any endorsement, and neither company has anything to do with this
repository.

All of it lives in the repo on purpose. A badge service or an image host would mean a third party
gets a request, and a log entry, every time someone opens one of these pages. This way the page
asks nothing of anyone.

Nothing else belongs in this folder.
