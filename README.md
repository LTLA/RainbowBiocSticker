# How I did it:

1. Download the Bioconductor sticker PDF from 
https://github.com/Bioconductor/BiocStickers/blob/master/Bioconductor/Bioconductor.pdf.
2. Unpack the PDF into its components in [Inkscape](https://inkscape.org/).
3. Create a slanted rainbow background with the appropriate colors.
4. Extract the quaver, title and border from the unpacked sticker and use it to clip the background.
5. Create a more transparent version of the rainbow background and use it to clip the hexagonal white background.
6. Assemble the now-colored components into a sticker.

The `rainbow_BioC_raw.svg` file contains all of the raw pieces required to perform the above.
The `rainbow_BioC.svg` file contains the final product for exporting the drawing to the desired format.
