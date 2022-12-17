# orthic
Orthic shorthand resources

## Editing Locally
### Initial Setup
- Clone to get the repo
- cd into the repo
- Configure Ruby version management as you like it (rbenv, asdf, rvm, etc.) so you can Ruby
    - As of 2022-12-12, GitHub Pages is using Ruby 2.7.4, per [Github Pages Dependency Versions](https://pages.github.com/versions/).
- `bundle install` so you have all the dependencies
- Make sure you have `mkcert` installed
- `mkcert localhost` so you get a cert and key for Jekyll to serve your site via HTTPS locally.

### Live Editing
Run:

```
bundle exec jekyll serve --incremental --livereload --ssl-cert localhost.pem  --ssl-key localhost-key.pem --host localhost --baseurl '
```

Then open the URL it shows as the server address, which is usually https://localhost:4000/.
