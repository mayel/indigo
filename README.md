build & run locally with:
	npm run serve --incremental

publish to IPFS:
	npm run build
	cd _site
	ipfs add -r .
	ipfs pin add -r /ipfs/<hash_of_folder> # this tells node to cache content permanently
	ipfs name publish <hash_of_folder>
