Backlinking is a crucial part of why this solution work so well. mkdocs uses a plugin called `roamlinks` to take care of turning `[[backlinks]]` into real links.

!!!caution
    Page is a work in progress due to some weirdness with escaping. Take a look at the git repo in [plain text for this page](https://git.zetdemo.ktz.me/ironicbadger/self-hosted-zettelkasten-wiki/raw/branch/main/docs/Writing%20Tips.md) to get a better understanding for now.

## Customising the text of a link

Let's say the name of your note does not make sense in the context of sentence into which the backlink has been placed, what then? We can customise the text of a link like so:

```md
    Before: [[Writing Tips]]
	After: [[Writing Tips|Custom Text]]
```
	
That would create a link to this note with the text "Custom Text" in the mkdocs rendered output and Obsidian preview pane.

## Backlinking to sub-headers

We can take this even further by customising the text of a link to a specific sub-heading within a back-linked page as well. Like so:

```md
Before: [[Writing Tips#Backlinking to sub-headers]]
After: [[Writing Tips#Backlinking to sub-headers|Custom Text]]
```
	
[[Gitea#docker-compose snippet]]
	
This would create a link to a sub-heading within this note and display the text "Custom Text" in the mkdocs rendered output and Obsidian preview pane.