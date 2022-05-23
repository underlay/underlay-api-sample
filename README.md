# Underlay API Sample

The Underlay API provides easy access to the data contained in each collection.
For now, you do not need any authentication for accessing the API. Simply [`fetch`](https://github.github.io/fetch/) the endpoint to get the data you need!

## Running the sample

- `npx serve`
- Navigate to the HTML files located under the `samples` directory

## Avaiable endpoints

- Endpoint: `/api/${namespace}/${collection}/downloads/latest`
- Sample: `/samples/download.html`

This returns the `collection` owned by `namespace`, in JSON format.
