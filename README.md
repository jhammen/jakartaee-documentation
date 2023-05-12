# jakartaee-tutorial-playbook
Root repo for building the Jakarta EE Tutorial site (from different repos).

To build, run:

```
mvn clean verify
```

The output will be in `target/generated-docs`. To view, just open file://<project dir>/target/generated-docs/index.html.

## Author Mode

Antora supports an Author Mode that lets you work with local branches and your local worktree. This requires that you keep a local copy of `antora-playbook.yml`. Read [these instructions](https://docs.antora.org/antora/latest/playbook/author-mode/) for details. 

Once you've created this file, you can use the `author-mode` Maven profile:

```
mvn compile -Pauthor-mode
```
