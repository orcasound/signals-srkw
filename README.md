# signals-srkw

Release-based archive of SRKW signal types

Goal: collaborate with other bioacoustic experts to agree upon new versions of SRKW signal catalogs based on open-access audio data and open source scripts that process raw data into optimally-formatted media under Orcasound's BY-SA-NC Creative Commons license. 

Context: With licensing of data and software agreed upon in advance, an authoritative source of SRKW signals can be shared with between bioacoustic and educational efforts from CA to AK, in the US and Canada -- across the SRKW range. Such a source could catalyze new presentations of the processed media (audio clips and visualizations like spectrograms) beyond the [data products currently organized by Orcasound](https://orcasound.net/data/product/), the HALLO project's KW call catalogue ([deployed prototype](https://orca.research.sfu.ca/catalogue/) | [Github repo](https://github.com/coastal-science/call-catalog-viewer)), and other related learning resources on the web.

**Tasks for next release:**

- Upload examples of Orcasound whistles
- Upload some examples from Riesch and Ford (2008)
- Upload examples of Orcasound click proposed types

**Task for subsequent releases: **
- Upload Ford 2022 files as raw calls
- Upload examples of Wieland whistles (from pub)

**Other (longer-term) tasks:**
- Generate a list of files to process for Orcasound data products
- Write script to read the list of files to process and generate:

1. A FLAC and .ogg format audio clip (e.g. with custom filtering and/or padding to a uniform duration via Python or ffmpeg)
2. A B&W spectrogram & waveform akin to John Ford's 2022 catalog images in .png format
3. A spectrogram created with an optimal accessibility color palette in .png format
4. Thumbnails of each type of spectrogram 
5. A .yaml file in the format of the [HALLO catalogue viewer](https://github.com/coastal-science/call-catalog-viewer)

- Re-write the HTML-generating code in Emily's repo to ingest the .yaml file and the media directory as it builds new web-based verions of an Orcasound signal-catalogue.
- Re-write the HTML-generating code for the 2018 SRKW Ford-Osborne audio/spectrogram data
- Write a script to generate a "Vocabulary" that replicates what Val and CC students created back in ~2002


