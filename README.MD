# ApiService

A simple HTTP API service for making requests with token authentication.

## Installation

```bash
npm install api-service
```

## Usage

```typescript
import ApiService from 'api-service';

const apiService = new ApiService('your-token', 'https://api.example.com');

// Make a GET request
apiService
  .get('/endpoint')
  .then((response) => console.log(response))
  .catch((error) => console.error(error));
```

## Contributing

Please see the CONTRIBUTING file.

License
MIT
