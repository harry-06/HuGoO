# Hugo-Static-Site-Generator
Static website generator- useful for quick building of prototypes





Steps to install Hugo in macOS
==============================

Step 1:Install Hugo
====================
1.Install Homebrew (package manager) for macOS from https://brew.sh/
2.Install hugo :brew install hugo
3.Verify your install : hugo version

Step2 :Create Hugo Site
=======================
4.Create new site : hugo new site test_site

Step 3:Add Hugo Theme
======================
5.Download a theme into the same-named folder.
   Choose a theme from https://themes.gohugo.io/, or
   create your own with the "hugo new theme <THEMENAME>" command.

Command:
 git submodule add https://github.com/g1eny0ung/hugo-theme-dream.git themes/dream

	# Edit your config.toml configuration file
	# and add the Dream theme.
	echo 'theme = "Dream"' >> config.toml

6. Perhaps you want to add some content. You can add single files
   with "hugo new <SECTIONNAME>/<FILENAME>.<FORMAT>".
   hugo new posts/my-first-post.md

7. Start the built-in live server via "hugo server".
hugo server -D

