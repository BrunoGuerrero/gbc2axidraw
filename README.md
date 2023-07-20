# sprite2axidraw, a sprite to AxiDraw SVG convereter
Destined to convert a low-palette image into a set an SVG ready for the AxiDraw.

Converts each pixel into a shape (Square, circle or cross), with each pixels grouped by color in layers numbered for use in AxiDraw.
Squares and Circles still require hatch fill for filling out the shapes. 

Initially built to convert GameBoy Camera images to AxiDraw.

## Usage

Simply open the html page with your favorite brwoser (But preferably with Chrome. I haven't tested other ones.) then open up your image of choice. 

This will automatically try to convert the image into an SVG, in which each pixel will be converted into the shape of your choice.

Click Download to download your SVG. Please note that the SVG can not be opened with a web browser, but will be perfectly fine with Inkscape.
