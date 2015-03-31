# Contribution Guidelines

When making any contributions/changes/updates to the repository, please follow the following guidelines:

### General Guidelines

- Seperate words in filenames with a hyphen: `Example-of-a-Filename`
- Use [Title Case](http://blog.apastyle.org/apastyle/2012/03/title-case-and-sentence-case-capitalization-in-apa-style.html) for filenames and titles if possible, http://titlecapitalization.com/# can help.
- Do not upload any image or non-text files, host them on [pomf.se](http://pomf.se/), [mediacru.sh](https://mediacru.sh/), [volafile.io](https://volafile.io/) etc. and link to them from here like so:

```
Image files: (displays the image, alternative text shows while the image loads)
![alternative text](http://link-to-image.image-extension)

Other: (displays the text and links to file)
[text](http://link-to-file)
```
This is to keep the Git repository light.
- Use [markdown](https://github.com/gitlabhq/gitlabhq/blob/master/doc/markdown/markdown.md) instead of HTML in .md files, GitLab strips out any HTML not contained in code blocks (the inline-HTML section on their [markdown guide](https://github.com/gitlabhq/gitlabhq/blob/master/doc/markdown/markdown.md) is incorrect)
- Put 2 spaces at the end of a line if you want a line break, in addition to starting the next line on a newline ([markdown is strange like that](http://meta.stackexchange.com/questions/26011/should-the-markdown-renderer-treat-a-single-line-break-as-br)).