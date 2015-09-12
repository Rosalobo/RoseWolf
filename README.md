Rose's Website
---

How to start the site:

```
npm run start 
```

This will watch all files for changes and will rebuild the site whenever a file changes.

To serve the site run:

```
serve
```

Then go to `http://127.0.0.1:3000` and you should see the site. Refresh to see any changes. 

To add a new post, add a markdown file to the `drafts` folder with the format: 

```
YYYY-MM-DD-title
```

A new post should like this:

```
Title
---

This is my content.
```

How to push to GirHub:

1. modify files

2. save files

3. `git add .`

4. `git commit -am "changes"`

5. `git push origin gh-pages`

