ABCD-Downloader
===============

Script to download various kernels/initrd-images for abcd.

Quickstart
----------

	mv /etc/abcd/download.d /etc/abcd/download.d.dist
	git clone git://github.com/steigr/abcd-downloader.git /etc/abcd/download.d
	chmod 0700 /etc/abcd/download.d/abcd-downloader
	ln -s /etc/abcd/download.d/abcd-downloader /usr/sbin/abcd	downloader
	abcd-downloader