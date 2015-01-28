# Hugo Cheatsheet

Hugo is a fast and flexible static site generator built in GoLang - http://gohugo.io

## Table of Contents

- Hugo Commands
- Folder Structure
- Global Variables
- Site Variables
- Page Variable


## Hugo Commands

```
$ hugo help

A Fast and Flexible Static Site Generator built with
love by spf13 and friends in Go.

Complete documentation is available at http://gohugo.io

Usage:
  hugo [flags]
  hugo [command]

Available Commands:
  server                    Hugo runs its own webserver to render the files
  version                   Print the version number of Hugo
  check                     Check content in the source directory
  benchmark                 Benchmark hugo by building a site a number of times
  new [path]                Create new content for your site
  help [command]            Help about any command

 Available Flags:
  -b, --baseUrl="": hostname (and path) to the root eg. http://spf13.com/
  -D, --buildDrafts=false: include content marked as draft
  -F, --buildFuture=false: include content with datePublished in the future
      --config="": config file (default is path/config.yaml|json|toml)
  -d, --destination="": filesystem path to write files to
      --disableRSS=false: Do not build RSS files
      --disableSitemap=false: Do not build Sitemap file
      --editor="": edit new content with this editor, if provided
  -h, --help=false: help for hugo
      --log=false: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
      --noTimes=false: Don't sync modification time of files
      --pluralizeListTitles=true: Pluralize titles in lists using inflect
  -s, --source="": filesystem path to read files relative from
      --stepAnalysis=false: display memory and timing of different steps of the program
  -t, --theme="": theme to use (located in /themes/THEMENAME/)
      --uglyUrls=false: if true, use /filename.html instead of /filename/
  -v, --verbose=false: verbose output
      --verboseLog=false: verbose logging
  -w, --watch=false: watch filesystem for changes and recreate as needed

Use "hugo help [command]" for more information about that command.
```
