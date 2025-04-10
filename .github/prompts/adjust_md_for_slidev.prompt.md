2. Copy the .md file from the PDF_file_folder to the root of this workspace and rename it to `slides.md`
3. open that `slides.md` file
4. for the `slides.md` file do:
	1. Wrap source code paragraphs with proper Markdown formatting for better readability.
	2. Add a horizontal line and a blank line above each first-level heading for better structure, but only before, not also after the heading.
	3. Add an additional horizontal line at the beginning of the file
	4. remove all markdown bold notations (remove all ** ) from header lines
5. create a folder named "public" if doesn't exist in the root of the workspace
6. copy all image files from the PDF_file_folder to that public folder 
7. in the `slides.md` file, adjust all paths of images to be absolute to the root like `/<imagename>`
8. [start the slidev server](start_slidev_and_fix_errors.prompt.md)