# signals-srkw

Release-based archive of SRKW signal types

**Goal:** collaborate with other bioacoustic experts to agree upon new versions of SRKW signal catalogs that are based on open-access audio data and open source scripts. Both audio data and code should be clearly licensed before being shared in a new release of this repository. The default licensing for audio data and data products is Orcasound's BY-SA-NC Creative Commons license. The license for code in this repo is the MIT allowing easy sharing of new catalog designs with other bioacousticians (e.g. for birds or bats, or whales other than orcas). 

**Context:** 

With licensing of data and software agreed upon in advance, we hope that an authoritative source of SRKW signals can be shared between bioacoustic and educational and annotation efforts from CA to AK, in the US and Canada -- across the range of the SRKW. Such a source could catalyze new presentations of the processed media (audio clips and visualizations like spectrograms) beyond the [data products currently organized by Orcasound](https://orcasound.net/data/product/), [Orcasound's learning resources](https://www.orcasound.net/learn/), the HALLO project's KW call catalogue ([deployed prototype](https://orca.research.sfu.ca/catalogue/) | [Github repo](https://github.com/coastal-science/call-catalog-viewer)), and other related learning resources on the web.

With agreement on the names of signals and their definition through a dictionary we can label audio data more-efficiently as a community of bioacsoustcians. Such labels are valuable in organizing training materials for human listeners and in generating training data to refine [Artificial Intelligence for Orcas](https://ai4orcas.net). We hope agreeement can be reached through a [data label dictionary (shared Google spreadsheet) of Salish Sea signals](https://docs.google.com/spreadsheets/d/1pskIEYjIVQH0IPa10UBuAZHKaGsxs02_itSIZ1Z7oAw/edit?gid=0#gid=0) as well as detailed [discussions of signal categories within this repo's Github Discussions](https://github.com/orcasound/signals-srkw/discussions).

By sharing open signal catalogs with a UI that allows playback of audio (rather than only visual represenations like spectrograms or waveforms), we can help both humans and algorithms understand how to split and lump sounds into particular categories. This learned classification process also depends on and feeds back into consistent, standardized labeling of audio signals.

**Latest release:**

- Archive of the raw "Ford-Osborne tape" recordings
- Basic archive of the Ford-Osborne data products (audio clips and spectograms) that underly extant SRKW call catalogs:
  - [2002 version of the Orcasound open call catalog](https://www.orcasound.net/FordOsborneVocabulary/_SouthernVocabularyTable.html)
  - [2018 version of the Orcasound open call catalog](https://www.orcasound.net/data/product/SRKW/call-catalog/srkw-orca-call-catalog.html)

**Tasks for next release:**

- [ ] SRKW whistles
  - [x] Upload examples of whistles (ideally open Orcasound examples of all 7 types)
  - [ ] Upload some example whistles from the Riesch and Ford (2008) recordings provided by John Ford in January, 2024
- [ ] Add clicks
  - [ ] [Discuss SRKW echolocation nomenclature](https://github.com/orcasound/signals-srkw/discussions/14), standardizing if possible with HALLO project
  - [ ] Upload examples of Orcasound's proposed echolocation categories (e.g from Max's [SRKW click catalog](https://www.orcasound.net/portfolio/srkw-click-catalog/) to catalyze preliminary labeling for new click detector development)

**Task for subsequent releases:**
- Upload Ford 2022 files as raw calls (audio data underlying the new HALLO 2024 KW call catalog)
- Upload examples of Wieland whistles (from pub)?

**Other (longer-term) tasks:**
- Generate a list of files to process for Orcasound data products
- Write script to read the list of files to process and generate:

1. A FLAC and .ogg format audio clip (e.g. with custom filtering and/or padding to a uniform duration via Python or ffmpeg)
2. A B&W spectrogram & waveform akin to John Ford's 2022 catalog images in .png format (possibly with call parts indicated?)
3. A color spectrogram created with an optimal accessibility color palette in .png format
4. Thumbnails of each type of spectrogram 
5. A .yaml file in the format of the [HALLO catalogue viewer](https://github.com/coastal-science/call-catalog-viewer)

- Re-write the HTML-generating code in Emily's repo to ingest the .yaml file and the media directory as it builds new web-based verions of an Orcasound signal-catalogue.
- Re-write the HTML-generating code for the 2018 SRKW Ford-Osborne audio/spectrogram data
- Write a script to generate a "Vocabulary" that replicates what Val and CC students created back in ~2002


