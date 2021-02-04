# Freeform Notes

* works with the directory structure not against
* can index any types of file the user specifies with a conversion to text
* can export bookmarks from firefox and grabs title, description, and text from direct page
* supports templates
* draw a graph of a set of notes based on any user word or phrase
* works with notes in 1 or more repositories or local directories
* maybe works with git submodules as well to bring in external sets of notes

e.g. 

"pdf": {
    name: "Adobe PDF",
    command: "pdf2txt {{file}}"
}

* uses directory hierarchy to guide topics
* default recognition of different file types e.g. source files so can be included/ignored
* creates a $USER/.config/freeform specified in FREEFORM_CONFIG_PATH directory
* extract words from images
* identifies changes in the directory structure and reindexes accordingly