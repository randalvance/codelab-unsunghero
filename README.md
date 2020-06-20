# Codelabs - Unsung Hero

![Merge to master - Build and Deploy](https://github.com/randalvance/codelab-unsunghero/workflows/Merge%20to%20master%20-%20Build%20and%20Deploy/badge.svg)

[https://codelab-unsunghero.netlify.app](https://codelab-unsunghero.netlify.app)

# Run Locally

Run the following command commands
```
npm install
npm start --codelabs-dir=codelabs
```

# Convert Markdown to HTML

You can refer to [this article](https://medium.com/@zarinlo/publish-technical-tutorials-in-google-codelab-format-b07ef76972cd).

We need to install `claat` using `go get` (Requires Go)
```
go get github.com/googlecodelabs/tools/claat
```
Then run the command while inside the `codelabs` folder.
```
claat export path_to_md_file
```
# Build and Deploy
Run the following command
```
npm build --codelabs-dir=codelabs
```
It will generate a deployable `dist` folder.

# Authoring Markdown Files

[Codelab Formatting Guide](https://github.com/googlecodelabs/tools/blob/master/FORMAT-GUIDE.md)