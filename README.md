# Genkit Plugin Template

## Description

My basic plugin template for genkit

### Example use case :

just for testing only, get cuisine for all around the world

## Installation

-   run `npm install genkitx-test-template-plugin`
-   insert `myCustomPlugin` into your genkit plugin's list
-   access it via browser on `localhost:4000` or you can hit in via curl

```
curl --location 'http://localhost:4000/api/runAction?batch=1' \
--header 'Content-Type: application/json' \
--data '{
    "0": {
        "key": "/flow/myCustomPlugin",
        "input": {
            "start": {
                "input": {
                    "prompt": "where does this plugin made?"
                }
            }
        }
    }
}'
```

## Reference

https://medium.com/@retzd/easy-guide-to-build-your-own-generative-ai-plugin-with-genkit-abfb1bbe8bd6

License : Apache 2.0
