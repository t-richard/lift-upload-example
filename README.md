# Lift upload construct examples

This is related to the following [Lift PR](https://github.com/getlift/lift/pull/103)

To test this, run this command

```bash
`serverless deploy`
```

In the output, look for the API gateway endpoint then replace it in `dist/fetch.html`, 
`dist/axios.html` and `dist/multiple.html` **but keep the `/upload-url` path at the end.**

Now run `serverless landing:upload` and click on the static website URL in the output.

You should see a landing page with links pointing to each page. Feel free to test everything and look at the code!

> You can also test this with REST APIs by uncommenting the relevant lines in `serverless.yml`