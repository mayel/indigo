build & run locally with:
	npm run serve --incremental 

publish to IPFS:
	cd _site
	ipfs add -r . 
	ipfs name publish [key]
