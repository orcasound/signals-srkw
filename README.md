# signals-srkw

Release-based archive of SRKW signal types

**Goal:** collaborate with other bioacoustic experts to agree upon new versions of SRKW signal catalogs based on open-access audio data and open source scripts that process raw data into optimally-formatted media under Orcasound's BY-SA-NC Creative Commons license. 

**Context:** With licensing of data and software agreed upon in advance, an authoritative source of SRKW signals can be shared  between bioacoustic and educational and annotation efforts from CA to AK, in the US and Canada -- across the range of the SRKW. Such a source could catalyze new presentations of the processed media (audio clips and visualizations like spectrograms) beyond the [data products currently organized by Orcasound](https://orcasound.net/data/product/), the HALLO project's KW call catalogue ([deployed prototype](https://orca.research.sfu.ca/catalogue/) | [Github repo](https://github.com/coastal-science/call-catalog-viewer)), and other related learning resources on the web.

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
  - [ ] Discuss SRKW echolocation nomenclature, standardizing if possible with HALLO project
  - [ ] Upload examples of Orcasound's proposed echolocation categories (to catalyze preliminary labeling for new click detector development)

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


