

## How to add pages:

1. Create .md file in /docs/.... (e.g., docs/tanki2.0/page1.md)


2. Add to nav: in mkdocs.yml:
<pre>
nav:
- New Section:
    - New Page: path to page1.md
</pre>
Directory Structure:
<pre>
docs/  
├─ section-name (doesnt have to be the same as the nav name)/  
│  ├─ page1.md  
│  └─ page2.md  
</pre>

### Order in nav: = menu order.
### In nav you can create anything you want with any name you want. the only thing that matters is the final md page path, if the folders and the nav names dont match up that doesnt matter. Only the md directory should match