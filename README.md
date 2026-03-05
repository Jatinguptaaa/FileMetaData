# File Metadata API

Simple Express API to upload a file and return its metadata.

## Features

- Upload a single file via `multipart/form-data`
- Returns JSON with:
  - `name`
  - `type`
  - `size`

## Run locally

1. Install dependencies:
	`npm install`
2. Start the server:
	`npm start`
3. Open:
	`http://localhost:3000`

## API

- **Endpoint:** `POST /api/fileanalyse`
- **Form field name:** `upfile`

### Example response

```json
{
  "name": "photo.png",
  "type": "image/png",
  "size": 24567
}
```
