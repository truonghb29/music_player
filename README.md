
## FE

1. Clone the repository:
   ```bash
   git clone https://github.com/truonghb29/music_player.git
   cd FE
   npm install

2. Set up environment variables:
Create a .env file in the root directory.
Add the necessary environment variables as shown in the .env.development file.
    ```bash
    NEXT_PUBLIC_BACKEND_URL=http://localhost:8005/api/v1/
    NEXT_PUBLIC_BACKEND_PUBLIC=http://localhost:8005/images/
    GITHUB_ID=
    GITHUB_SECRET=
    NEXTAUTH_URL=http://localhost:3000
    NEXTAUTH_SECRET=
    MY_SECRET_TOKEN=
    GOOGLE_ID=
    GOOGLE_SECRET=
    TOKEN_EXPIRE_NUMBER=86000
    TOKEN_EXPIRE_UNIT=seconds
    NEXT_PUBLIC_FRONTEND_PUBLIC=http://localhost:3000/

3. Start the development server:
   ```bash
   npm run dev

## BE

1. Clone the repository:

   ```bash
   cd BE

2. Install the dependencies:
   ```bash
      npm install

## Environment Variables
1. Create a .env file in the root directory and add the following variables:
   ```bash
      PORT=8005
      MONGO_URL=
      NODE_ENV=dev
      
      #SET UP ACCESS TOKEN
      JWT_ACCESS_TOKEN_SECRET=
      JWT_ACCESS_TOKEN_EXPIRE=1d
      
      #SET UP REFRESH TOKEN
      JWT_REFRESH_TOKEN_SECRET=
      JWT_REFRESH_TOKEN_EXPIRE=1d
      
      #ADMIN EMAIL
      ADMIN_EMAIL=
      
      #FLAG TO AUTO GENERATE DATABASE
      SHOULD_INIT=true
      INIT_PASSWORD=
      
      #CONFIG EMAIL
      SENDER_EMAIL=
      PASSWORD_EMAIL=
      HOST_EMAIL=smtp.gmail.com
      EMAIL_PREVIEW=false
      
      RENDER_BE=
      
      GITHUB_CLIENT_ID=
      GITHUB_CLIENT_SECRET=
      
      GITHUB_URL_CALLBACK=
      
      #PAYMENT
      PAYOS_CLIENT_ID=
      PAYOS_API_KEY=
      PAYOS_CHECKSUM_KEY=


## Running the Application
1. Start the development server:
   ```bash
      npm run dev

2. The application will be running at http://localhost:8005

