# Useful Jekyll Terminal Commands

Common commands for working with Jekyll site locally.  
Copy and paste into terminal as needed.

---

```sh

# Serve the site locally with live reload
bundle exec jekyll serve
# Starts a local web server at http://localhost:4000 and auto-refreshes on changes

# Find a running Jekyll server (if you closed the terminal)
lsof -i :4000
# Lists the process using port 4000

# Stop the process
kill -9 <PID>
# Replace <PID> with the number from the previous command to stop the process

# If port 4000 is busy, use another port
bundle exec jekyll serve --port 4001
# Serves the site at http://localhost:4001

# Clean up generated files
bundle exec jekyll clean
# Removes the _site and .jekyll-cache folders
# Use before troubleshooting, after major changes, or ensure site is rebuilt from scratch.
# Not needed for every update — only when you suspect stale files may cause issues.

```

---

*These commands are for local development and maintenance of your Jekyll site.  
No commands here will sync or push to a remote repository.*