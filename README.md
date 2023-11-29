<a name="readme-top"></a>
# dacs4-002
I adapted it from this repository (https://github.com/saalikmubeen/talkhouse) for study purposes.
WebRTC based peer to peer video calling and messaging web app build with MERN stack. 

<!-- TABLE OF CONTENTS -->
<details>
    <summary>Table of Contents</summary>
    <ul>
	    <li>
            <a href="#installation">Installation</a>
            <ul>
                <li><a href="#run-server-side"> Run Server Side</a></li>
                <li><a href="#run-client-side"> Run Client Side</a></li>
            </ul>
        </li>
    </ul>
</details>

<!-- INSTRUCTION -->
# Installation

*Make sure you have Node.js installed*

Clone project:

```
git clone git@github.com/Alex2o9z/dacs4-002.git
```

## Run Server Side

Navigate to the "server" directory:

```
cd server
```

Install server dependencies:

```
npm install
```

Create a `.env` file in the `server` folder and set up the required environment variables:

```
MONGO_URI_DEV = your_mongodb_uri
JWT_SECRET = any_string_you_want
```

Start development server with nodemon:

```
npm run dev
```

## Run Client Side

Navigate to the "client" directory:

```
cd client
```

Install client dependencies:

```
npm install
```

Start the react development server:

```
npm run start
```

Your app is now ready at http://localhost:3000. To use the video call feature, it's recommended to use the same browser with a different profile.

Modify the API (Server URL) in `client\src\api\api.ts` (line 14) and `client\src\socket\socketConnection.ts` (line 193) as needed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
