# Sitemap Parser

This project is one of the assignments of [Gophercises](https://courses.calhoun.io) from Jon Calhoun.

To run this project:

```
    go run main.go --url <the path to the HTML file to parse> --depth <number os levels to seek on the sitemap>
```

Example:

```
    go run main.go --url https://gophercises.com --depth 2
```

To generate the XML file, you should add `> map.xml` after the command.
Example:

```
    go run main.go --url https://gophercises.com --depth 2 > map.xml
```
