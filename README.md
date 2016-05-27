linter-markdown-external#51 MWE
===============================

https://github.com/AtomLinter/linter-markdown/issues/51

Steps to reproduce:

1.  Make sure atom has markdown-linter package:
```apm install markdown-linter```

2.  Run the following:

  ```bash
  git clone git@github.com:kachkaev/linter-markdown-51.git
  cd linter-markdown-51
  npm install
  ```

3.  Add the project to Atom

4.  Open `README.md` and see an error on line 4 (`no-literal-urls`)

5.  Replace `"external (not working)"` with `"external"` in `.remarkrc`

6.  Return to `README.md` and edit something

7.  ![PROFIT!](/error.png)
