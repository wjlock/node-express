# node-express

Node allows javascipt to be used as a backend language.

## Setting up node

First, you will need to initialize node. To do so, type navigate to your project folder in terminal and type npm init -y.

```text
npm init -y
```

This command allows us to use node. the "-y' assigns everything a default value.

You can run files in node through the command line by typing out node + the file name.

```text
node index.js
```

##  Modules
Modules allow you to import data from another file. This is helpful to store things like functions that do not need to be part of the core logic.

In Node, module.exports is an object that will hold the code to be exported. We can use dot-notation to add the code we want to export to this object.

For example, we can create the object
```js
module.exports.beBasic() => "That's so fetch"
```

And then export that to our index file and run the funciton there.







