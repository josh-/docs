# git_pull


Executes a simple git pull command







git_pull |
-----|----
Supported platforms | ios, android, mac
Author | @KrauseFx, @JaviSoto



**2 Examples**

```ruby
git_pull
```

```ruby
git_pull(only_tags: true) # only the tags, no commits
```





**Parameters**

Key | Description
----|------------
  `only_tags` | Simply pull the tags, and not bring new commits to the current branch from the remote




<hr />
To show the documentation in your terminal, run
```no-highlight
fastlane action git_pull
```

<a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/git_pull.rb" target="_blank">View source code</a>

<hr />

<a href="/actions"><b>Back to actions</b></a>