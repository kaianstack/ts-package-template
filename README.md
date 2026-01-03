
### Init
1. `git clone https://github.com/kaianstack/ts-package-template .`

2. `npx --yes rimraf .git`

3. `cp .env.example .env`

4. Change the name in package.json or `npm pkg set name="package-name"`

5. `npm install`

### How to:
#### Build
`npm run build`
#### Run tests
`npm run test`
#### Start
`npm run start`
#### Add package
`npm install package-name`
#### Add your package from github that was built on top of the template:
`npm install github:username/repo`
#### Remove package
`npm uninstall package-name`
If package was installed from github, you need to uninstall it by "name" from package.json.

