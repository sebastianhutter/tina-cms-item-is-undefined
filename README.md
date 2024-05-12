# tinacms field not found

Nested rich-text templates throw field not found.

Install [hugo](https://gohugo.io/installation/)

Install node modules
```bash
npm i
```
Run the demo environment
```bash
npx tinacms dev -c "hugo server -D -p 1313 --bind 0.0.0.0"
```

## Reproduce error

Open http://localhost:1313/admin

Navigate to `Posts` -> `Hello World` 

Open the embed `Create row with columns`

Open any of the `Add column to row` embeds

The error message `item is undefined` is shown

The rendered version of the hello world page can be accessed via http://localhost:1313/posts/hello-world