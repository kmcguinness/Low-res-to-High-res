# Low-res-to-High-res
Applescript droplet for use with Scene 7.  Pulls high res images out of S7 based on the low res image file name.

#### Installation
1. Save the droplet to your desktop or somewhere easy to access.
2. Create a folder on your desktop named `images-high-res`.
3. You may need to edit the droplet itself based on your S7 folder structure.  The file path you want to edit is in the `set_myUrl` variable at the end of the droplet.

#### Use
1. Gather the low res images you need high res versions of in Finder
2. Drop the image(s) on the droplet
3. Hit `Run`.
4. The high res images will download into the folder you created above.

#### Notes
For ease of use the droplet does not throw error messages.  If you do not see it run, check your: low res file names, `images-high-res` folder, `set_myUrl` variable.
