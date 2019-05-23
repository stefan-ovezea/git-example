# Git Example

## Task list

1. Create new branch starting from develop, named like `feature-<firstName>-<lastName>`
2. Add a new file `style.css`
3. Commit & Push
4. Referennce `style.css` in `index.html`, by adding the following line just above the `<title>` tag:

```
<link rel="stylesheet" href="style.css">
```

5. Commit & Push
6. Change the text in the `<h1>` tag with anything you want.
7. Commit & Push
8. Add any text below `<h1>` tag
9. Commit & Push
10. Squash
11. Push
12. Switch to `develop` branch and `pull`
13. Switch back to your named branch and rebase `develop`
14. Create new branch from the current one, named `feature-<firstName>-<lastName>-2`
15. Add the following code snippet to `style.css`:

```
h1 {
    color: red;
}
```

16. Commit (don't push)
17. Switch to your initial branch and merge the secondary branch into this one
18. Create a `Pull Request` from your branch with `develop` as base
