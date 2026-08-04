# IPTV Resources

High-resolution channel logos sourced from Plex's Gracenote lineup feeds.

## Logo collections

- `logos/directv-new-york/` — 852 DIRECTV New York lineup logos
- `logos/verizon-fios-queens/` — 629 Verizon Fios Queens lineup logos
- `logos/spectrum-northern-manhattan/` — 612 Charter Spectrum Northern Manhattan lineup logos
- `logos/optimum-new-york/` — 600 Optimum New York lineup logos
- `logos/channel-logos/` — 296 normalized US and Mexico channel logos for automated matching

Files retain their Plex source resolution and are named using channel number, channel name, call sign, and HD designation where available.

## Catalog artwork

- `Catalogs/Collections/` — 24 collection images
- `Catalogs/Decades/` — 11 decade images and one JSON index
- `Catalogs/Genre/` — 19 genre images
- `Catalogs/Streaming/` — 34 streaming-service images, including animated variants
- `Catalogs/Actors/` and `Catalogs/Directors/` — reserved for future artwork

## Raw URL format

```text
https://raw.githubusercontent.com/ayala/iptv-resources/main/logos/directv-new-york/<filename>.png
https://raw.githubusercontent.com/ayala/iptv-resources/main/logos/verizon-fios-queens/<filename>.png
https://raw.githubusercontent.com/ayala/iptv-resources/main/logos/spectrum-northern-manhattan/<filename>.png
https://raw.githubusercontent.com/ayala/iptv-resources/main/logos/optimum-new-york/<filename>.png
https://raw.githubusercontent.com/ayala/iptv-resources/main/logos/channel-logos/<filename>.png
https://raw.githubusercontent.com/ayala/iptv-resources/main/Catalogs/<category>/<filename>
```

The files in `logos/channel-logos/` use normalized names such as `cnn-us.png`
and `hbo-xtreme-mx.png`. The final country suffix allows consumers to restrict
matching to the active lineup country.
