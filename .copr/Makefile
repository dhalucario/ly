srpm:
	cd $(spec)
	make github
	rpmbuild -vv -bs ly.spec --define "_srcrpmdir $(outdir)"
