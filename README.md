<!-- # HNG12 Stage 0 API

## Description
A simple public API for HNG12 Stage 0 that returns:
- My registered email
- Current date/time in ISO 8601 format
- My GitHub repository URL

## Endpoint
**GET** https://hng-1orb.onrender.com/

### Example Response
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

### Running Locally
- git clone https://github.com/Olayanju-1234/HNG.git
- cd hng
- cd stage0
- yarn install
- node index.js

### [Hire Node.js Developers](https://hng.tech/hire/nodejs-developers) -->

# HNG12 Stage 1 - Number Classification API

## Description
An API that classifies a number based on:
- Prime status
- Perfect number status
- Armstrong number property
- Odd/Even classification
- Sum of digits
- A fun fact from the Numbers API

## Endpoint
**GET** `https://hng-1orb.onrender.com/api/classify-number?number=371`

### Example Response
```json
{
  "number": 371,
  "is_prime": false,
  "is_perfect": false,
  "properties": ["armstrong", "odd"],
  "digit_sum": 11,
  "fun_fact": "371 is an Armstrong number because 3^3 + 7^3 + 1^3 = 371"
}
```

## Running Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/Olayanju-1234/HNG.git
   cd Stage1
   ```
2. Install dependencies:
   ```bash
   yarn install
   ```
3. Start the server:
   ```bash
   node index.js
   ```

## Hire Node.js Developers
[Hire Node.js Developers](https://hng.tech/hire/nodejs-developers)

