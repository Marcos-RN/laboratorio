## Build

Build the image:

```console
C:\Users\antonio> docker build -t docker-compile-javac .
```

## Run

Run the following command to start the container:

```console
C:\Users\antonio> docker run -v %cd%/volume:/app docker-compile-javac
```

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.