# catalog-signals-srkw

Versioned archive of SRKW signal types

Goal: collaborate with other bioacoustic experts to agree upon new versions of SRKW signal catalogs based on open access audio data and open source scripts that process raw data into optimally-formatted media under Orcasound's BY-SA-NC Creative Commons license. 

Context: an authoritative source of SRKW signals can be shared with other bioacoustic and educational efforts across the SRKW range. Such a souce could catalyze new presentations of the processed media (audio clips and visualizations like spectrograms) beyond the [data products currently organized by Orcasound](https://orcasound.net/data/product/).

Tasks:

- Upload Ford 2022 files as raw calls
- Upload examples of Orcasound click proposed types
- Upload examples of Orcasound whistles
- Upload examples of Wieland whistles (from pub)

- Generate a list of files to process for Orcasound data products
- Write script to read the list of files to process to generate:

1. A FLAC and .ogg format audio clip (e.g. with custom filtering and/or padding to a uniform duration via Python or ffmpeg)
2. A B&W spectrogram & waveform akin to John Ford's 2022 catalog images in .png format
3. A spectrogram created with an optimal accessibility color palette in .png format
4. Thumbnails of each type of spectrogram 
5. A .yaml file in the format of the [HALLO catalogue viewer](https://github.com/coastal-science/call-catalog-viewer)

- Re-write the HTML-generating code in Emily's repo to ingest the .yaml file and the media directory as it builds new web-based verions of an Orcasound signal-catalogue.


