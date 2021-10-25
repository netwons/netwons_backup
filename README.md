
# netwons_backup #

Scans backup folders on target sites. Searches archived files in the folders it finds.


1 --> files/extensions.txt - This adds new extensions to the file, for example: by adding in the form of .example allows you to retry all the possibilities tried in the new extensions.

2 --> files/files.txt - It can scan these folders according to the extensions you added, by giving them new file names.

3 --> files/folders.txt - Recursively scans the specified folders. You can add to this list yourself.


# Installation #
1-`cd ohmybackup`

2-`go build ohmybackup.go`

# Run #

`./ohmybackup --hostname target.com `

