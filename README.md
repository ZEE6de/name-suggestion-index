[![build](https://github.com/osmlab/name-suggestion-index/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/osmlab/name-suggestion-index/actions/workflows/test.yml)
[![npm version](https://badge.fury.io/js/name-suggestion-index.svg)](https://badge.fury.io/js/name-suggestion-index)
[![](https://data.jsdelivr.com/v1/package/npm/name-suggestion-index/badge?style=rounded)](https://www.jsdelivr.com/package/npm/name-suggestion-index)


# name-suggestion-index ("NSI")

Canonical features for OpenStreetMap, collected manually and via the [NSI Collector](https://github.com/ideditor/nsi-collector) planet scan.

## What is it?

The goal of this project is to maintain a [canonical](https://en.wikipedia.org/wiki/Canonicalization)
list of commonly used features for suggesting consistent spelling and tagging in OpenStreetMap.

>
> 👉 &nbsp; [Watch the video](https://2019.stateofthemap.us/program/sat/mapping-brands-with-the-name-suggestion-index.html) from our talk at State of the Map US 2019 to learn more about this project!
>

## Browse the index

You can browse the name-suggestion-index and check Wikidata links for accuracy at <https://nsi.guide>.

<img alt="nsi.guide" src="https://raw.githubusercontent.com/osmlab/name-suggestion-index/main/docs/img/nsi.png"/>


## How it's used

When mappers create features in OpenStreetMap, they are not always consistent about how they
name and tag things. For example, we may prefer `McDonald's` tagged as `amenity=fast_food`
but we see many examples of other spellings (`Mc Donald's`, `McDonalds`, `McDonald’s`) and
taggings (`amenity=restaurant`).

Building a canonical feature index allows two very useful things:

- We can suggest the most "correct" way to tag things as users create them while editing.
- We can scan the OSM data for "incorrect" features and produce lists for review and cleanup.

<img width="1017px" alt="Name Suggestion Index in use in iD" src="https://raw.githubusercontent.com/osmlab/name-suggestion-index/main/docs/img/nsi-in-iD.gif"/>

*The name-suggestion-index is in use in iD when adding a new item*

Currently used in:

- [Rapid](https://github.com/facebook/Rapid)
- [iD](https://github.com/openstreetmap/iD) (see above)
- [Vespucci](http://vespucci.io/tutorials/name_suggestions/)
- [JOSM presets](https://josm.openstreetmap.de/wiki/Help/Preferences/TaggingPresetPreference) available
- [Osmose](http://osmose.openstreetmap.fr/en/errors?item=3130)
- [osmfeatures](https://github.com/westnordost/osmfeatures)
- [Go Map!!](https://github.com/bryceco/GoMap)
- [StreetComplete](https://streetcomplete.app/) (and [SCEE](https://github.com/Helium314/SCEE))
- [Every Door](https://github.com/Zverik/every_door)
- [All The Places](https://github.com/alltheplaces/alltheplaces)


## About the index

See [the project wiki](https://github.com/osmlab/name-suggestion-index/wiki) for details.


## Participate!

We're always looking for help!

- Read [the Code of Conduct](CODE_OF_CONDUCT.md) and remember to be kind to one another.
- See [the project wiki](https://github.com/osmlab/name-suggestion-index/wiki) for info about how to contribute to this index.

If you have any questions or want to reach out to a maintainer, ping any of these folks:
 - [archpdx (arch0345)](https://github.com/arch0345)
 - [Bryan Housel](https://github.com/bhousel)
 - [Cj Malone](https://github.com/Cj-Malone)
 - [kjonosm](https://github.com/kjonosm)
 - [快乐的老鼠宝宝 (LaoshuBaby)](https://github.com/LaoshuBaby)
 - [Minh Nguyễn (1ec5)](https://github.com/1ec5)
 - [Tim Smith (tas50)](https://github.com/tas50)
 - [UKChris-osm](https://github.com/UKChris-osm)

We can be found in:
- [OpenStreetMap US Slack](https://slack.openstreetmap.us/) (`#poi` or `#general` channels)
- [OpenStreetMap World Discord](https://discord.gg/openstreetmap)


## License

**name-suggestion-index** is available under the [3-Clause BSD License](https://opensource.org/licenses/BSD-3-Clause).
See the [LICENSE.md](LICENSE.md) file for more details.
