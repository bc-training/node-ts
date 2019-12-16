# GraphQL NodeJs Typescript skeleton

![Coverage:branches](./badges/badge-branches.svg)
![Coverage:functions](./badges/badge-functions.svg)
![Coverage:lines](./badges/badge-lines.svg)
![Coverage:statements](./badges/badge-statements.svg)

* To `install` the NodeJS packages

	```bash
	npm i
	```

* To `compile` and `start` the project

	```bash
	npm run compile
    npm run build
	
	npm run start
	npm run build:start
	```

* To `lint` project code

    ```bash
    npm run tslint
    npm run tslint:nofix
    ```

* To `bump` a new version, create a tag and push it.

    Follow the semantic release rules `major.minor.patch`

    * **major** - Breaking changes
    * **minor** - Next features
    * **patch** - Bug fixes
  
    ```bash
    npm run bump-major-version
    npm run bump-minor-version
    npm run bump-patch-version
    ```

    or manually provide a message
  
    ```bash
    npm version minor --force -m "project starter kit (minor changes)" && git push --follow-tags
    ```
    