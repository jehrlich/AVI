# AVI
unofficial proof-of-concept for AVI Interoperability 

Intended as a prototype for an artifact managed by the AVI Interoperability Standards Workgroup. The repo should keep versioned specifications for any standards as they are being developed, and serve as a site for public dissemination of standards as they are developed. I envision this repo as being maintained by a subset of the standards workgroup in such a way that all members of the workgroup may contribute without necessarily learning intracacies of git or github.

This README could be a contents page with links to resources.

Because it is what I am familiar with, I am setting this up with a source docuemnt using 
- OpenAPI 3 (I prefer YAML to JSON, we can use either or both)
-  ReDoc
-  Github Pages
-  Github Actions to trigger a ReDoc build when the main branch is updated 

It would be easy to add automated messaging to Slack when the site is rebuilt.

This is a DRAFT. Please fix or forgive errors.

My working environment:
- VSCode editor with plugins including
    - OpenAPI (Swagger) Editor  https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi
    - openapi-lint https://marketplace.visualstudio.com/items?itemName=mermade.openapi-lint
    - YAML https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml
    - YAML ❤️ JSON  https://marketplace.visualstudio.com/items?itemName=hilleer.yaml-plus-json
