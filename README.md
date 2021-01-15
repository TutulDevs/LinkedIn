# LinkedIn Clone using Tailwind CSS

[Live link](https://linkedin-tailwind.netlify.app)

## Run in dev mode

In dev mode you need the full heavy tailwind.css because when you add Tailwind classes in your HTML, it will works directly, in some milliseconds. Be sure to run : `npm run buildcss:dev` if you use `commit_and_push.sh` you don't need it.

When you need to edit your tailwind.config.js (like testing colors) or your custom CSS (`main.css`), you can run `npm run onchange` on one tab, to see those edits live. You don't need it if you only edit your HTML with Tailwind classes.

## Run in production

Compile and commit a light tailwind.css file with `npm run buildcss:prod`. If you use `./commit_and_push.sh "commit message"`, you don't need to run it.
