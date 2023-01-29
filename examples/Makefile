apply:
	@cd simple-local-wiki && npx -y @tuxounet-k2/cli@latest ./k2.inventory.yaml apply

clean:
	@cd simple-local-wiki && npx -y @tuxounet-k2/cli@latest ./k2.inventory.yaml clean


dev-apply: 
	@cd simple-local-wiki && node ../../../k2/dist/index.js ./k2.inventory.yaml apply

dev-clean:
	@cd simple-local-wiki && node ../../../k2/dist/index.js ./k2.inventory.yaml clean
