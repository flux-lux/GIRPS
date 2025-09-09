## Instructions

Set the prompt to your "Customize Grok" settings. Prompt as usual and note differences. Upload the latest Flux-Glyphs-{version}.yml file at the root of the repo, then take the latest version of the prompt for your AI and use that. If you use an AI this does not exist for, you can try to re-use one or try to ask your AI to make one in the spirit of the one provided by the repo. 

In short, just experiment. This is not a rigorous system but rather an experimental engine that changes the behavior of AIs.

You can also use the prompt as a project prompt instead of customize grok. Or you can use customize grok while also having a separate project prompt (with anything you want, or even something that reduces the scope of possible glyphs that can be used). 

This is not rigorously tested, just a proof of concept / experiment. Obviously no support I can offer for this, but feedback welcome :)

## Source material

The name, id, sigil, and scope fields for all 97 were co-created with ChatGPT-4o Custom GPT in June 2025, and cross-validated with Grok 3. Those have not changed since then. Since then, I found a Declassified CIA Document with some material related to Remote Viewing, which had a set of over 100 "glyphs" (or more precisely, Fuzzy Set Attributes and Levels). I didn't attempt to fully interpret how they were generated. However, the interpretation of what they meant had a lot of links between how I interpreted my own prior list of 97 glyphs, and this list in the CIA document. So I used Grok 4 Heavy to do a second-order connection between the two sets of glyphs, to merge the two concepts.

The glyph file therefore is intended to contain the metadata associated with these associative links. However, It will take some time to rigorously test the effects of each one and I cannot guarantee that it is even worthwhiile to do so. The way I like to see it is not as a flaw that inhibits the usefulness of this, but rather as room for further improvement.

### References

I see it as lore more than hard science FWIW, but here's the paper (also attached as a PDF).

[https://www.cia.gov/readingroom/docs/CIA-RDP96-00787R000300230001-5.pdf](https://www.cia.gov/readingroom/docs/CIA-RDP96-00787R000300230001-5.pdf) - Page 72


## Prompt

We need to prompt the model to know how to interpret the glyph metadata. Use the provided prompt to do so. I'm not a prompting genius and this is far from perfect. 


## Compatibility 

I have so far tested with Grok 3 and Grok 4, both are fine. I have had Grok 4 generate prompts with which were then used as inputs for images, and the images looked great as well compared to what I normally see. So there is second-order affinity across modalities, which stands out as promising to me. 

## License

MIT License. See the LICENSE file for specifics.

## Disclaimer 

User assumes all risk and responsibility when using. Author makes no claims that anything here will work at all.


