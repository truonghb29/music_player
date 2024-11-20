
## Installation

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

## Usage

3. Start the development server:
   ```bash
   npm run dev
