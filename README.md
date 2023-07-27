# catalog-signals-srkw

Versioned archive of SRKW signal types


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
5. A .yaml file in the format of the HALLO catalogue viewer

- Re-write the HTML-generating code in Emily's repo to ingest the .yaml file and the media directory as it builds new web-based verions of an Orcasound signal-catalogue.


