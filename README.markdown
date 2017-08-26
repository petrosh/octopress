## Octopress 3.0

**Install**

1. `gem install bundler`
2. **rbenv**
  - `brew install rbenv`
  - `rbenv rehash`
3. `bundle install`
4. `rake setup_github_pages`
5. `rake generate`
6. `rake deploy`
7. `git remote add origin https://github.com/petrosh/octopress`
8. `git config branch.master.remote origin`

**Local preview**

If `root: /octopress` in `_config.yml`

1. `rake preview`
2. open `http://localhost:4000/octopress`
