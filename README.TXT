Add the following section to your .git/config and chmod a+x .rezip/rezip.sh

[filter "rezip"]
	clean = ./.rezip/rezip.sh -0
	smudge = ./.rezip/rezip.sh -9
