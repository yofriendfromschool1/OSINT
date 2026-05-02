# OSINT
OSINT Tools, if you have anymore tools/websites/resources please create an issue or fork and let me know!
https://intelx.io
https://www.truepeoplesearch.com
https://onlinereverselookup.com
https://www.officialusa.com
https://www.idcrawl.com
https://www.duplichecker.com/reverse-image-search.php
https://start.me/p/L1rEYQ/osint4all
https://whitepages.com
https://www.yellowpages.com/
https://usa-official.com/
https://radaris.com/
https://www.vehiclehistory.com/license-plate-search
https://osintframework.com/
https://haveibeenpwned.com/
https://github.com/smicallef/spiderfoot -- default with kail linux
https://hackertarget.com/recon-ng-tutorial/#install -- default with kail linux
https://pimeyes.com/en
https://tineye.com/
https://ahmia.fi/
https://github.com/Greenwolf/social_mapper
https://whatsmyname.app
https://urlscan.io/
https://dnsdumpster.com/
https://epieos.com/
https://opencorporates.com/
https://thatsthem.com/
https://openminds.exopaedia.org/EXIF%20samples/exif%2069667671.egLsAwK4.Staroselciweb64_6625.htm
https://exiftool.org/
https://twitonomy.com/
https://tinfoleak.com/
https://www.codeofaninja.com/tools/
https://imginn.com/
https://www.linkedin.com/feed/
https://www.exploit-db.com/google-hacking-database
https://www.maxmind.com/en/geoip-web-services-demo
https://github.com/jivoi/awesome-osint
https://geospy.web.app (must use chrome, brave)
https://picarta.ai/
https://findpiclocation.com/
https://galaxy.ai/
https://www.findthatspot.io/
https://www.reddit.com/r/wherewasthistaken/
https://www.whereisthisphoto.com/
https://chatgpt.com/g/g-TOADOq5ud-photo-locator
https://whereisthisplace.net/
https://osm-search.bellingcat.com/
https://geoseeer.com/
https://web.archive.org/
https://inteltechniques.com/tools/index.html
https://usersearch.org/
https://wigle.net/
https://www.crunchbase.com/
https://www.zoominfo.com/
https://www.opensanctions.org/
https://www.openownership.org/en/
https://www.epfindia.gov.in/site_en/index.php
https://www.apollo.io/
https://www.dnb.com/en-us/products/dnb-hoovers.html
https://hunter.io/
https://prospeo.io/domain-search
https://anymailfinder.com/email-finder-by-domain
https://snov.io/email-finder
https://dehashed.com/
https://getprospect.com/email-finder/email-finder-by-domain
https://www.cyberbackgroundchecks.com
https://www.city-data.com/
http://www.icrimewatch.net/
https://omar-thing.site
https://one-plus.github.io
https://www.osintcombine.com/free-osint-tools/osint-bookmark-stack
https://www.osint.industries/
https://29a.ch/photo-forensics/#forensic-magnifier
https://map-making.app/

## AI Image Prompt OSINT ppl-sonar-reasoning-pro-high
You are an expert OSINT geolocation analyst. Analyze this image and determine 
the most precise location possible — ideally down to the street address. 

Follow these steps:

1. **Visual Feature Extraction**: Identify all visible clues — building 
   architecture, roof styles, construction materials, signage (language, 
   brands, phone numbers), street furniture, road markings, lane patterns, 
   utility poles, and vehicle types/license plates.

2. **Vegetation & Terrain Analysis**: Identify tree species, grass type, 
   soil color, and any geological features. Use these to narrow the climate 
   zone and hemisphere.

3. **Contextual Clues**: Analyze sun angle and shadow direction to estimate 
   latitude and time of day. Note weather conditions, sky color, and lighting.

4. **Cultural & Regional Indicators**: Look for driving side (left/right), 
   power line styles, crosswalk designs, curb types, and any visible brand 
   names or store chains that are region-specific.

5. **Narrow Down**: Start with continent → country → region → city → 
   neighborhood → street. Provide your reasoning at each level.

6. **Final Answer**: Give your best estimate as:
   - Full address (if possible)
   - GPS coordinates (latitude, longitude)
   - Confidence level (low/medium/high)
   - Key evidence that led to your conclusion

Be as specific as possible. Do not stop at "somewhere in Europe" — push to 
the most granular level the evidence supports.

## Second prompt grok 4.20 multi agent
You are an elite OSINT geolocation specialist and former GeoGuessr champion with expert knowledge of global architecture, botany, geology, urban planning, street furniture, utility infrastructure, vehicle/license plate standards, and signage across every country.

I will upload an image. Your task is to determine the most precise real-world location possible (ideally down to street address, building, or GPS coordinates with uncertainty radius).

Follow this protocol exactly. Explain your reasoning at every step. Do not jump to conclusions or favor one hypothesis early.

1. **Raw Objective Observations** (list only facts, no interpretation yet):
   - Describe visible plants/trees (species if identifiable, leaf shape, bark, growth habit — distinguish native vs. ornamental).
   - Architecture and materials (roof type, wall construction, windows, colors, specific styles).
   - Infrastructure (utility poles, power lines, curbs, sidewalks, road markings, fencing, street lights — note exact designs, colors, shapes).
   - Topography, slopes, shadows (estimate sun position, possible latitude/hemisphere/season).
   - Any text, signs, license plates, vehicles, clothing, or cultural markers (do OCR precisely).
   - Overall setting (urban density, rural, suburban tract housing, etc.).

2. **Diagnostic Analysis** (reason category by category):
   - Climate & vegetation: What region would have this exact combination of native plants + planted species?
   - Built environment & infrastructure: Which countries/regions use these exact architectural styles, pole designs, curb types, roof tiles?
   - Cultural & other cues: Driving side, signage language/script, vehicle types.

3. **Shortlist**: Give 3–5 candidate locations (countries/regions/cities) that are geographically spread out at first. Make a table comparing how well each matches the clues. Assign confidence scores. Explicitly note what would disprove each.

4. **Narrow & Pinpoint**: Eliminate candidates step by step. Choose the strongest match. Suggest the most likely specific spot (address, intersection, or lat/long). Provide exact Google search terms or Street View descriptions to verify (e.g., "search for [specific tree species] near [architecture style] in [city]").

5. **Final Answer & Confidence**: State your best guess clearly with coordinates/address if possible, confidence percentage, uncertainty radius (e.g., "within 50 meters"), and remaining weaknesses. Suggest what extra information (another photo angle, date) would improve it.

Be extremely thorough on unique combinations (e.g., specific house style + tree species + utility pole type). Actively try to disprove your leading hypothesis. Avoid hallucinating details or claiming to view maps you can't access.
