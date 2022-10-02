## package.json peerDependencies

By adding a package in peerDependencies you are saying:

My code is compatible with this version of the package.
If this package already exists in node_modules, do nothing.
If this package doesn’t already exist in the node_modules directory or it is the wrong version, don’t add it. But, show a warning to the user that it wasn’t found.
