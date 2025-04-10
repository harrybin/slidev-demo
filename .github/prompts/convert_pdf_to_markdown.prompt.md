The goal is to convert a PDF file into a markdown file including images.
For this `marker` from [](https://github.com/VikParuchuri/marker) is used.
1. call the "marker_single" commandline tool for the pdf in the root folder in the project including the option "--output_dir" for the current folder like `marker_single [path_to_the_pdf_file_to_use] --use_llm --output_dir .`
   - wait for the tool to finish, the tool needs a very long time to complete (it may need longer than one minute)
   - the tool creates a new folder with the name of the pdf file (without the extensions) and states this also in the console starting with "Saved markdown to"; we call this folder PDF_file_folder further on
2. continue with [steps for slidev conversion](adjust_md_for_slidev-prompt.md)