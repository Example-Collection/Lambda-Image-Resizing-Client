# Lambda-Image-Resizing-Client

- Sample client application for testing [https://github.com/Example-Collection/Lambda-Image-Resizing-Example]().

## Setup

- (1) Follow and deploy Lambda function for image resizing, using [this code](https://github.com/Example-Collection/Lambda-Image-Resizing-Example).

- (2) Clone this repository to your local machine.

```sh
git clone https://github.com/Example-Collection/Lambda-Image-Resizing-Client.git
```

- (3) Install all required dependencies.

```sh
yarn install
```

- (4) Create a file called `.env`, and add lambda's API Gateway endpoint as below.

```env
REACT_APP_IMAGE_UPLOAD_URL=https://your-api-gateway-endpoint.com
```

- (5) Start application, and begin testing!

```sh
yarn start
```
