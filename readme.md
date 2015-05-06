Manifest section for music-DSP:
===============================

Get repo:
---------

	see: http://source.android.com/source/downloading.html#installing-repo

	mkdir ~/.bin
	PATH=~/.bin:$PATH
	curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
	chmod a+x ~/.bin/repo


Create the tree:
----------------

	mkdir WORKING_DIRECTORY
	cd WORKING_DIRECTORY
	repo init -u https://github.com/musicdsp/manifest.git
	repo sync -j8


Now all is done ...
