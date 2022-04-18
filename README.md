# Create a simple AWS Lambda using Typescript
## Article Link
Please read the following article to learn how to set up typescript in a nodejs lambda package.

[Create a simple AWS Lambda using Typescript](https://medium.com/@valerio.uberti23/create-simple-aws-lambda-using-typescript-732c8a4a7a09)

## Build and Test
```
cd src
npm run compile
cd ..
sam build
sam local invoke -e events/event.json
```
