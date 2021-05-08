This repo has been created to rotate every motherboard schema present in Microhouse Technical Library.

As you may have noticed, every boards found in MTL and its clones (Total Hardware 1999, stason.org, UH19, etc) are "upside-down". We do not know the reason for that, but we'd like to correct this.
Unfortunately this is not trivial, because the schemas contain text. Thankfully, since the original images are vectorial, there's still a way to make a lot of it automatic, but we've stumbled accross some problems : 

I have run a script on every motherboards to rotate the text automatically, but some errors have been created by it. 90% of the rotated text is fine, but the remaining 10% is off and need to be corrected by a human on each schema.

Moreover, rotating the entire schema with scripts appeared to be buggy. This has to be made by hand as well.

Finally, some boards (Single Board Computers, etc) must NOT be rotated. Again these have to be found and removed by humans from this repo. Only ATX, AT and Baby AT motherboards need to be rotated. The rest has to be removed from this repo.


The reason of the existence of this repo is because it contains over 5100 images, so we can just not do it all by ourselves.

If you're willing to help us, please note that our program of choice to do edit the SVG files is [Inkscape](https://inkscape.org/).
