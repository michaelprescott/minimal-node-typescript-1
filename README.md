# minimal-node-typescript-1
Minimalistic Node + TypeScript Project - 1

About
=====
A minimalistic Node + TypeScript project.


Getting Started
---------------
1. Install NVM (Node Version Manager)
    * https://github.com/nvm-sh/nvm#installing-and-updating
2. Install Node.js using NVM
    * `nvm install node`
3. From the root of the project directory
    * `npm install`
    * `npm run start`


Configure Environment
=====================

Sublime Text
------------
When using Sublime Text plugins that require Node.js, and using NVM (Node Version Manager), Sublime cannot locate `node` to run plugins that depend on it.  To solve this problem:

1. Sublime > Preferences > Settings
2. Revise the Preferences.sublime-settings to specify the node_path. For example:

```
{
	"ignored_packages":
	[
		"Vintage",
	],
	"node_path": "/Users/yourusername/.nvm/versions/node/v17.3.1/bin/node"
}
```
