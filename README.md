# jamkit-node-bridge
A Node module that facilitates integration with Jamkit.

# How to use
To utilize the primitive functions of Jamkit from within your Node module:

```
export default (() => {
  Object.assign(this, require("jamkit-node-bridge"));

  return {
    ...
  }
)();
```
