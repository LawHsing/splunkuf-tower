
If you would like to instead upload the Splunk UF .tgz from your local ansible machine, you can do so by modifying the download_uf_tgz_from_splunk_servers (specifically setting either of them to "false") in ./group_vars/all

If a file with the same MD5 checksum is already present on the server, this project does not bother to redownload/upload the file.
