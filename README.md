# Codelabs - Unsung Hero

[https://codelab-unsung-hero.netlify.app](https://codelab-unsung-hero.netlify.app)

# Run Locally

Run the following command commands
```
npm install
npm start
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
npm build
```
It will generate a deployable `dist` folder.

# Authoring Markdown Files

[Codelab Formatting Guide](https://github.com/googlecodelabs/tools/blob/master/FORMAT-GUIDE.md)