This repository aims to provide a reproducible error for this stackoverflow question:  
https://stackoverflow.com/questions/76403957/next-js-export-build-fails-due-to-api-folder-how-to-ignore-it

## The issue

app/api folder creates an error during build when nextConfig.output is "export"

## How to reproduce issue

Run following command

- yarn install
- yarn export

This will produce following error

> Export encountered errors on following paths:
    /api/revalidate/route: /api/revalidate
